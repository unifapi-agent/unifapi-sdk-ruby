# Unifapi::SeoKeywordsForSiteResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Target domain echoed from the request. |  |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **view** | [**SeoKeywordView**](SeoKeywordView.md) |  |  |
| **total_count** | **Integer** | Total number of keywords available for the target in DataForSEO&#39;s database. | [optional] |
| **offset** | **Integer** | Offset applied to the results. | [optional] |
| **offset_token** | **String** | Pass this token as offset_token to fetch the next page of keywords. | [optional] |
| **results** | [**Array&lt;SeoKeywordItem&gt;**](SeoKeywordItem.md) | Keywords the domain is relevant for, with search volume, competition, difficulty, and intent. Each keyword is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoKeywordsForSiteResponse.new(
  target: null,
  location: null,
  language: null,
  view: null,
  total_count: null,
  offset: null,
  offset_token: null,
  results: null
)
```

