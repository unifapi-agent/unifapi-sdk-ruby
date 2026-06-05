# Unifapi::SeoKeywordSuggestionsResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seed_keyword** | **String** | Seed keyword echoed from the request. |  |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **view** | [**SeoKeywordView**](SeoKeywordView.md) |  |  |
| **total_count** | **Integer** | Total number of suggestions available for the request in DataForSEO&#39;s database. | [optional] |
| **offset** | **Integer** | Offset applied to the results. | [optional] |
| **offset_token** | **String** | Pass this token as offset_token to fetch the next page of suggestions. | [optional] |
| **results** | [**Array&lt;SeoKeywordItem&gt;**](SeoKeywordItem.md) | Keyword suggestions with search volume, competition, difficulty, and intent. Each keyword is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoKeywordSuggestionsResponse.new(
  seed_keyword: null,
  location: null,
  language: null,
  view: null,
  total_count: null,
  offset: null,
  offset_token: null,
  results: null
)
```

