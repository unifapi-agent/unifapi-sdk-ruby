# Unifapi::SeoBacklinksDomainPagesResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Target echoed from the request. |  |
| **view** | [**SeoBacklinksView**](SeoBacklinksView.md) |  |  |
| **total_count** | **Integer** | Total number of pages available in DataForSEO&#39;s database. | [optional] |
| **results** | [**Array&lt;SeoBacklinksDomainPageItem&gt;**](SeoBacklinksDomainPageItem.md) | Target pages ranked by backlink volume, with crawl data and backlink counters. Each page is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksDomainPagesResponse.new(
  target: null,
  view: null,
  total_count: null,
  results: null
)
```

