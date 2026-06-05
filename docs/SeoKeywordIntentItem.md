# Unifapi::SeoKeywordIntentItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **keyword** | **String** | Keyword phrase. |  |
| **search_intent** | **String** | Main search intent: informational, navigational, commercial, or transactional. | [optional] |
| **probability** | **Float** | Probability of the main search intent, where 1 is highest. | [optional] |
| **secondary_intents** | [**Array&lt;SeoKeywordIntentEntry&gt;**](SeoKeywordIntentEntry.md) | Other likely search intents for the keyword with their probabilities. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoKeywordIntentItem.new(
  keyword: null,
  search_intent: null,
  probability: null,
  secondary_intents: null
)
```

