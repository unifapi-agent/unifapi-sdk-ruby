# Unifapi::SeoBacklinksDomainIntersectionItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **domain** | **String** | Referring domain that links to the requested targets. |  |
| **intersections_count** | **Integer** | Number of the requested targets this domain links to. | [optional] |
| **referring_to** | [**Array&lt;SeoBacklinksDomainIntersectionTargetMetrics&gt;**](SeoBacklinksDomainIntersectionTargetMetrics.md) | Per-target backlink metrics, one entry per requested target this domain links to. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksDomainIntersectionItem.new(
  domain: null,
  intersections_count: null,
  referring_to: null
)
```

