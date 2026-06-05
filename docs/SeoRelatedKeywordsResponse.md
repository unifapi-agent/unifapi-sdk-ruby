# Unifapi::SeoRelatedKeywordsResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seed_keyword** | **String** | Seed keyword echoed from the request. |  |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **view** | [**SeoKeywordView**](SeoKeywordView.md) |  |  |
| **total_count** | **Integer** | Total number of related keywords available for the request in DataForSEO&#39;s database. | [optional] |
| **offset** | **Integer** | Offset applied to the results. | [optional] |
| **results** | [**Array&lt;SeoRelatedKeywordItem&gt;**](SeoRelatedKeywordItem.md) | Related keywords with search volume, competition, difficulty, intent, and their own related searches. Each keyword is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoRelatedKeywordsResponse.new(
  seed_keyword: null,
  location: null,
  language: null,
  view: null,
  total_count: null,
  offset: null,
  results: null
)
```

