# Unifapi::SeoKeywordOverviewResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **keywords** | **Array&lt;String&gt;** | Keywords echoed from the request. |  |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **view** | [**SeoKeywordView**](SeoKeywordView.md) |  |  |
| **results** | [**Array&lt;SeoKeywordItem&gt;**](SeoKeywordItem.md) | Per-keyword metrics: search volume, CPC, competition, difficulty, and intent. Each keyword is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoKeywordOverviewResponse.new(
  keywords: null,
  location: null,
  language: null,
  view: null,
  results: null
)
```

