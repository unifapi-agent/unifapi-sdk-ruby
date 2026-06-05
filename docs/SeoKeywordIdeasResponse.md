# Unifapi::SeoKeywordIdeasResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seed_keywords** | **Array&lt;String&gt;** | Seed keywords echoed from the request. |  |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **view** | [**SeoKeywordView**](SeoKeywordView.md) |  |  |
| **total_count** | **Integer** | Total number of keyword ideas available for the request in DataForSEO&#39;s database. | [optional] |
| **offset** | **Integer** | Offset applied to the results. | [optional] |
| **offset_token** | **String** | Pass this token as offset_token to fetch the next page of ideas. | [optional] |
| **results** | [**Array&lt;SeoKeywordItem&gt;**](SeoKeywordItem.md) | Keyword ideas with search volume, competition, difficulty, and intent. Each keyword is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoKeywordIdeasResponse.new(
  seed_keywords: null,
  location: null,
  language: null,
  view: null,
  total_count: null,
  offset: null,
  offset_token: null,
  results: null
)
```

