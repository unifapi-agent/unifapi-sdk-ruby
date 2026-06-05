# Unifapi::GeoMentionsCrossGroup

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **label** | **String** | Aggregation label that groups and identifies this target set in the response. |  |
| **target** | [**Array&lt;GeoMentionsTarget&gt;**](GeoMentionsTarget.md) | Up to 10 target entities, each a domain or a keyword. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::GeoMentionsCrossGroup.new(
  label: null,
  target: null
)
```

