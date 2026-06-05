# Unifapi::SeoKeywordIntentEntry

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **intent** | **String** | Search intent: informational, navigational, commercial, or transactional. |  |
| **probability** | **Float** | Probability of this intent, where 1 is highest. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoKeywordIntentEntry.new(
  intent: null,
  probability: null
)
```

