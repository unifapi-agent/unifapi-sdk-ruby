# Unifapi::SeoBacklinksPageIntersectionResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **targets** | **Array&lt;String&gt;** | The requested targets, in request order, echoed back. Each links_to entry&#39;s target matches one of these. |  |
| **view** | [**SeoBacklinksView**](SeoBacklinksView.md) |  |  |
| **total_count** | **Integer** | Total number of intersecting pages available in DataForSEO&#39;s database. | [optional] |
| **results** | [**Array&lt;SeoBacklinksPageIntersectionItem&gt;**](SeoBacklinksPageIntersectionItem.md) | Referring pages that link to the requested targets, with the backlinks to each target. Each page is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksPageIntersectionResponse.new(
  targets: null,
  view: null,
  total_count: null,
  results: null
)
```

