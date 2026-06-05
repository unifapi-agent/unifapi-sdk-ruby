# Unifapi::SeoKeywordHistoryResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **keywords** | **Array&lt;String&gt;** | Keywords echoed from the request. |  |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **results** | [**Array&lt;SeoKeywordHistoryItem&gt;**](SeoKeywordHistoryItem.md) | Historical metrics per keyword. Each keyword is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoKeywordHistoryResponse.new(
  keywords: null,
  location: null,
  language: null,
  results: null
)
```

