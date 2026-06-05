# Unifapi::GeoSerpTarget

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **value** | **String** |  |  |
| **domain** | **String** |  | [optional] |
| **present** | **Boolean** |  |  |
| **best_rank** | **Integer** |  | [optional] |
| **matches** | [**Array&lt;GeoSerpResultRef&gt;**](GeoSerpResultRef.md) |  |  |
| **citations** | [**Array&lt;GeoSerpCitation&gt;**](GeoSerpCitation.md) |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::GeoSerpTarget.new(
  value: null,
  domain: null,
  present: null,
  best_rank: null,
  matches: null,
  citations: null
)
```

