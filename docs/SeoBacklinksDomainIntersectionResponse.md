# Unifapi::SeoBacklinksDomainIntersectionResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **targets** | **Array&lt;String&gt;** | The requested targets, in request order, echoed back. Each referring_to entry&#39;s target matches one of these. |  |
| **view** | [**SeoBacklinksView**](SeoBacklinksView.md) |  |  |
| **total_count** | **Integer** | Total number of intersecting domains available in DataForSEO&#39;s database. | [optional] |
| **results** | [**Array&lt;SeoBacklinksDomainIntersectionItem&gt;**](SeoBacklinksDomainIntersectionItem.md) | Domains that link to the requested targets, with per-target backlink metrics. Each domain is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksDomainIntersectionResponse.new(
  targets: null,
  view: null,
  total_count: null,
  results: null
)
```

