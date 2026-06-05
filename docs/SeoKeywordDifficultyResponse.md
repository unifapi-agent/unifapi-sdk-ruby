# Unifapi::SeoKeywordDifficultyResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **keywords** | **Array&lt;String&gt;** | Keywords echoed from the request. |  |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **results** | [**Array&lt;SeoKeywordDifficultyItem&gt;**](SeoKeywordDifficultyItem.md) | Keyword difficulty per keyword. Each keyword is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoKeywordDifficultyResponse.new(
  keywords: null,
  location: null,
  language: null,
  results: null
)
```

