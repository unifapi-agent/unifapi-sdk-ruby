# Unifapi::SeoBacklinksPageIntersectionItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **url_from** | **String** | URL of the referring page that links to the targets. | [optional] |
| **domain_from** | **String** | Domain of the referring page. | [optional] |
| **intersections_count** | **Integer** | Number of the requested targets this page links to. | [optional] |
| **links_to** | [**Array&lt;SeoBacklinksPageIntersectionTargetLinks&gt;**](SeoBacklinksPageIntersectionTargetLinks.md) | Backlinks from this referring page to each requested target it links to, one entry per target. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksPageIntersectionItem.new(
  url_from: null,
  domain_from: null,
  intersections_count: null,
  links_to: null
)
```

