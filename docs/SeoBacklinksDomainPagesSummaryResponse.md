# Unifapi::SeoBacklinksDomainPagesSummaryResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Target echoed from the request. |  |
| **view** | [**SeoBacklinksView**](SeoBacklinksView.md) |  |  |
| **total_count** | **Integer** | Total number of pages available in DataForSEO&#39;s database. | [optional] |
| **results** | [**Array&lt;SeoBacklinksDomainPageSummaryItem&gt;**](SeoBacklinksDomainPageSummaryItem.md) | Per-page backlink summaries for the target, with backlink counters. Each page is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksDomainPagesSummaryResponse.new(
  target: null,
  view: null,
  total_count: null,
  results: null
)
```

