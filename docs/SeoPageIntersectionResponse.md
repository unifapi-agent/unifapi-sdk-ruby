# Unifapi::SeoPageIntersectionResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **pages** | **Array&lt;String&gt;** | Page URLs echoed from the request, in order. |  |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **view** | [**SeoKeywordView**](SeoKeywordView.md) |  |  |
| **total_count** | **Integer** | Total number of intersecting keywords available in DataForSEO&#39;s database. | [optional] |
| **results** | [**Array&lt;SeoPageIntersectionItem&gt;**](SeoPageIntersectionItem.md) | Keywords the requested pages rank for, with each page&#39;s ranking position. Each keyword is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoPageIntersectionResponse.new(
  pages: null,
  location: null,
  language: null,
  view: null,
  total_count: null,
  results: null
)
```

