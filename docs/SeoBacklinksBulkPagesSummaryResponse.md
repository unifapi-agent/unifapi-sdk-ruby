# Unifapi::SeoBacklinksBulkPagesSummaryResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **view** | [**SeoBacklinksView**](SeoBacklinksView.md) |  |  |
| **results** | [**Array&lt;SeoBacklinksBulkPageSummaryItem&gt;**](SeoBacklinksBulkPageSummaryItem.md) | Backlink summary for each requested page, domain, or subdomain. Each target is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksBulkPagesSummaryResponse.new(
  view: null,
  results: null
)
```

