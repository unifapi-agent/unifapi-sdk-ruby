# Unifapi::SeoBacklinksBulkPagesSummaryRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **targets** | **Array&lt;String&gt;** | Domains, subdomains, or pages to analyze (up to 1000). Domains/subdomains without https:// and www.; pages as absolute URLs. |  |
| **include_subdomains** | **Boolean** | Include backlinks pointing to the target&#39;s subdomains. Defaults to true. | [optional] |
| **rank_scale** | [**SeoBacklinksRankScale**](SeoBacklinksRankScale.md) |  | [optional] |
| **view** | [**SeoBacklinksView**](SeoBacklinksView.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksBulkPagesSummaryRequest.new(
  targets: null,
  include_subdomains: null,
  rank_scale: null,
  view: null
)
```

