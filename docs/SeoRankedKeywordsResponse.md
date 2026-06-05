# Unifapi::SeoRankedKeywordsResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Target domain or page echoed from the request. |  |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **view** | [**SeoKeywordView**](SeoKeywordView.md) |  |  |
| **total_count** | **Integer** | Total number of keywords the target ranks for in DataForSEO&#39;s database. | [optional] |
| **results** | [**Array&lt;SeoRankedKeywordItem&gt;**](SeoRankedKeywordItem.md) | Keywords the target ranks for, each with keyword metrics and the ranking position/URL. Each keyword is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoRankedKeywordsResponse.new(
  target: null,
  location: null,
  language: null,
  view: null,
  total_count: null,
  results: null
)
```

