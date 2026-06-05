# Unifapi::SeoKeywordIntentResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **keywords** | **Array&lt;String&gt;** | Keywords echoed from the request. |  |
| **language** | **String** |  |  |
| **results** | [**Array&lt;SeoKeywordIntentItem&gt;**](SeoKeywordIntentItem.md) | Search intent per keyword. Each keyword is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoKeywordIntentResponse.new(
  keywords: null,
  language: null,
  results: null
)
```

