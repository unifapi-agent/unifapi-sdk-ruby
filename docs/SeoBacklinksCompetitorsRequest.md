# Unifapi::SeoBacklinksCompetitorsRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Domain, subdomain, or page to analyze. A domain or subdomain is specified without https:// and www. (example.com); a page is specified as an absolute URL (https://example.com/blog/). |  |
| **main_domain** | **Boolean** | Treat the target and competitors as root domains rather than exact subdomains. | [optional] |
| **exclude_large_domains** | **Boolean** | Exclude very large generic domains (e.g. youtube.com, facebook.com) from results. | [optional] |
| **exclude_internal_backlinks** | **Boolean** | Exclude internal backlinks from the target&#39;s own subdomains. Defaults to true. | [optional] |
| **rank_scale** | [**SeoBacklinksRankScale**](SeoBacklinksRankScale.md) |  | [optional] |
| **filters** | [**SeoBacklinksCompetitorsRequestFilters**](SeoBacklinksCompetitorsRequestFilters.md) |  | [optional] |
| **order_by** | [**Array&lt;DataForSeoOrderByRule&gt;**](DataForSeoOrderByRule.md) | Sort the returned competitors. Each rule is {\&quot;field\&quot;,\&quot;dir\&quot;} with dir asc or desc; up to 3 rules, applied in order. Sortable fields: rank, intersections. | [optional] |
| **limit** | **Integer** | Maximum number of records to return. Defaults to 100. | [optional] |
| **offset** | **Integer** | Number of records to skip from the start of the results. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksCompetitorsRequest.new(
  target: null,
  main_domain: null,
  exclude_large_domains: null,
  exclude_internal_backlinks: null,
  rank_scale: null,
  filters: null,
  order_by: null,
  limit: null,
  offset: null
)
```

