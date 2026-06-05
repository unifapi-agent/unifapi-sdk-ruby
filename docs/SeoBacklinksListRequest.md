# Unifapi::SeoBacklinksListRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Domain, subdomain, or page to analyze. A domain or subdomain is specified without https:// and www. (example.com); a page is specified as an absolute URL (https://example.com/blog/). |  |
| **mode** | **String** | Result grouping: as_is returns every backlink (default), one_per_domain returns one per referring domain, one_per_anchor returns one per anchor. | [optional] |
| **backlinks_status_type** | [**SeoBacklinksStatusType**](SeoBacklinksStatusType.md) |  | [optional] |
| **include_subdomains** | **Boolean** | Include backlinks pointing to the target&#39;s subdomains. Defaults to true. | [optional] |
| **include_indirect_links** | **Boolean** | Include indirect links (via redirects or canonicals) to the target. Defaults to true. | [optional] |
| **exclude_internal_backlinks** | **Boolean** | Exclude internal backlinks from the target&#39;s own subdomains. Defaults to true. | [optional] |
| **rank_scale** | [**SeoBacklinksRankScale**](SeoBacklinksRankScale.md) |  | [optional] |
| **filters** | [**SeoBacklinksListRequestFilters**](SeoBacklinksListRequestFilters.md) |  | [optional] |
| **order_by** | [**Array&lt;DataForSeoOrderByRule&gt;**](DataForSeoOrderByRule.md) | Sort the returned backlinks. Each rule is {\&quot;field\&quot;,\&quot;dir\&quot;} with dir asc or desc; up to 3 rules, applied in order. Sortable fields: domain_from, url_from, url_to, domain_to, dofollow, is_new, is_lost, is_broken, rank, page_from_rank, domain_from_rank, backlink_spam_score, item_type, anchor, tld_from, semantic_location, first_seen, last_seen. | [optional] |
| **limit** | **Integer** | Maximum number of records to return. Defaults to 100. | [optional] |
| **offset** | **Integer** | Number of records to skip from the start of the results. | [optional] |
| **search_after_token** | **String** | Continuation token from a previous response, used to page past the 20,000-result offset limit. Keep all other parameters identical when paging. | [optional] |
| **view** | [**SeoBacklinksView**](SeoBacklinksView.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksListRequest.new(
  target: null,
  mode: null,
  backlinks_status_type: null,
  include_subdomains: null,
  include_indirect_links: null,
  exclude_internal_backlinks: null,
  rank_scale: null,
  filters: null,
  order_by: null,
  limit: null,
  offset: null,
  search_after_token: null,
  view: null
)
```

