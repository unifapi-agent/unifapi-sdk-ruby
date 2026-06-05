# Unifapi::SeoBacklinksReferringNetworksRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Domain, subdomain, or page to analyze. A domain or subdomain is specified without https:// and www. (example.com); a page is specified as an absolute URL (https://example.com/blog/). |  |
| **network_address_type** | **String** | Group referring networks by individual IP (ip, default) or by subnet (subnet). | [optional] |
| **backlinks_status_type** | [**SeoBacklinksStatusType**](SeoBacklinksStatusType.md) |  | [optional] |
| **include_subdomains** | **Boolean** | Include backlinks pointing to the target&#39;s subdomains. Defaults to true. | [optional] |
| **include_indirect_links** | **Boolean** | Include indirect links (via redirects or canonicals) to the target. Defaults to true. | [optional] |
| **exclude_internal_backlinks** | **Boolean** | Exclude internal backlinks from the target&#39;s own subdomains. Defaults to true. | [optional] |
| **internal_list_limit** | **Integer** | Maximum number of entries kept in each referring_links_* breakdown map. Defaults to 10. | [optional] |
| **rank_scale** | [**SeoBacklinksRankScale**](SeoBacklinksRankScale.md) |  | [optional] |
| **filters** | [**SeoBacklinksReferringNetworksRequestFilters**](SeoBacklinksReferringNetworksRequestFilters.md) |  | [optional] |
| **backlinks_filters** | [**SeoBacklinksAnchorsRequestBacklinksFilters**](SeoBacklinksAnchorsRequestBacklinksFilters.md) |  | [optional] |
| **order_by** | [**Array&lt;DataForSeoOrderByRule&gt;**](DataForSeoOrderByRule.md) | Sort the returned referring networks. Each rule is {\&quot;field\&quot;,\&quot;dir\&quot;} with dir asc or desc; up to 3 rules, applied in order. Sortable fields: rank, backlinks, backlinks_spam_score, referring_domains, referring_main_domains, referring_pages, referring_ips, referring_subnets, broken_backlinks, broken_pages, first_seen, lost_date. | [optional] |
| **limit** | **Integer** | Maximum number of records to return. Defaults to 100. | [optional] |
| **offset** | **Integer** | Number of records to skip from the start of the results. | [optional] |
| **view** | [**SeoBacklinksView**](SeoBacklinksView.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksReferringNetworksRequest.new(
  target: null,
  network_address_type: null,
  backlinks_status_type: null,
  include_subdomains: null,
  include_indirect_links: null,
  exclude_internal_backlinks: null,
  internal_list_limit: null,
  rank_scale: null,
  filters: null,
  backlinks_filters: null,
  order_by: null,
  limit: null,
  offset: null,
  view: null
)
```

