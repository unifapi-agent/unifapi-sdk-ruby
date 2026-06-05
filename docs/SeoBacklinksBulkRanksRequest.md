# Unifapi::SeoBacklinksBulkRanksRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **targets** | **Array&lt;String&gt;** | Domains, subdomains, or pages to analyze (up to 1000). Domains/subdomains without https:// and www.; pages as absolute URLs. |  |
| **rank_scale** | [**SeoBacklinksRankScale**](SeoBacklinksRankScale.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksBulkRanksRequest.new(
  targets: null,
  rank_scale: null
)
```

