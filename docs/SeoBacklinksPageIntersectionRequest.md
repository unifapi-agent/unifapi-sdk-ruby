# Unifapi::SeoBacklinksPageIntersectionRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **targets** | **Array&lt;String&gt;** | Domains, subdomains, or pages to find common referring pages for (1-20). Order is preserved as the 1-based index in the response. |  |
| **exclude_targets** | **Array&lt;String&gt;** | Domains, subdomains, or pages to exclude (up to 10). Pages linking to these are dropped. | [optional] |
| **intersection_mode** | **String** | all (default) returns pages linking to any target; partial returns only pages linking to every target. | [optional] |
| **backlinks_status_type** | [**SeoBacklinksStatusType**](SeoBacklinksStatusType.md) |  | [optional] |
| **include_subdomains** | **Boolean** | Include backlinks pointing to the target&#39;s subdomains. Defaults to true. | [optional] |
| **include_indirect_links** | **Boolean** | Include indirect links (via redirects or canonicals) to the target. Defaults to true. | [optional] |
| **exclude_internal_backlinks** | **Boolean** | Exclude internal backlinks from the target&#39;s own subdomains. Defaults to true. | [optional] |
| **internal_list_limit** | **Integer** | Maximum number of entries kept in each referring_links_* breakdown map. Defaults to 10. | [optional] |
| **rank_scale** | [**SeoBacklinksRankScale**](SeoBacklinksRankScale.md) |  | [optional] |
| **filters** | [**SeoBacklinksPageIntersectionRequestFilters**](SeoBacklinksPageIntersectionRequestFilters.md) |  | [optional] |
| **order_by** | [**Array&lt;DataForSeoOrderByRule&gt;**](DataForSeoOrderByRule.md) | Sort the intersecting referring pages. Prefix each field with the 1-based target index, e.g. 1.rank. Each rule is {\&quot;field\&quot;,\&quot;dir\&quot;} with dir asc or desc; up to 3 rules, applied in order. Sortable fields: dofollow, is_new, is_lost, is_broken, rank, page_from_rank, domain_from_rank, backlink_spam_score, item_type, anchor, tld_from, semantic_location, first_seen, last_seen. | [optional] |
| **limit** | **Integer** | Maximum number of records to return. Defaults to 100. | [optional] |
| **offset** | **Integer** | Number of records to skip from the start of the results. | [optional] |
| **view** | [**SeoBacklinksView**](SeoBacklinksView.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksPageIntersectionRequest.new(
  targets: null,
  exclude_targets: null,
  intersection_mode: null,
  backlinks_status_type: null,
  include_subdomains: null,
  include_indirect_links: null,
  exclude_internal_backlinks: null,
  internal_list_limit: null,
  rank_scale: null,
  filters: null,
  order_by: null,
  limit: null,
  offset: null,
  view: null
)
```

