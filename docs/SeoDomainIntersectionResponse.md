# Unifapi::SeoDomainIntersectionResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target1** | **String** | First domain echoed from the request. |  |
| **target2** | **String** | Second domain echoed from the request. |  |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **view** | [**SeoKeywordView**](SeoKeywordView.md) |  |  |
| **total_count** | **Integer** | Total number of intersecting keywords available in DataForSEO&#39;s database. | [optional] |
| **results** | [**Array&lt;SeoDomainIntersectionItem&gt;**](SeoDomainIntersectionItem.md) | Keywords shared by the two domains, with each domain&#39;s ranking position. Each keyword is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoDomainIntersectionResponse.new(
  target1: null,
  target2: null,
  location: null,
  language: null,
  view: null,
  total_count: null,
  results: null
)
```

