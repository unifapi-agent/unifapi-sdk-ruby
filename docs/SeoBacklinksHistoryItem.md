# Unifapi::SeoBacklinksHistoryItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **date** | **String** | Date of this monthly snapshot. |  |
| **new_backlinks** | **Integer** | Backlinks gained during the period. | [optional] |
| **lost_backlinks** | **Integer** | Backlinks lost during the period. | [optional] |
| **new_referring_domains** | **Integer** | Referring domains gained during the period. | [optional] |
| **lost_referring_domains** | **Integer** | Referring domains lost during the period. | [optional] |
| **crawled_pages** | **Integer** | Target pages crawled as of this snapshot. | [optional] |
| **rank** | **Integer** | Backlink rank of the target, similar to PageRank (0-1000 by default). | [optional] |
| **backlinks** | **Integer** | Number of backlinks pointing to the target. | [optional] |
| **backlinks_spam_score** | **Integer** | Average spam score of the referring pages, 0-100. | [optional] |
| **first_seen** | **String** | Date DataForSEO first found a backlink for the target. | [optional] |
| **lost_date** | **String** | Date the last backlink was lost, if the target currently has none. | [optional] |
| **broken_backlinks** | **Integer** | Number of backlinks pointing to broken (4xx/5xx) pages of the target. | [optional] |
| **broken_pages** | **Integer** | Number of broken target pages that still receive backlinks. | [optional] |
| **referring_domains** | **Integer** | Number of referring domains pointing to the target. | [optional] |
| **referring_main_domains** | **Integer** | Number of referring root domains pointing to the target. | [optional] |
| **referring_pages** | **Integer** | Number of referring pages pointing to the target. | [optional] |
| **referring_ips** | **Integer** | Number of referring IP addresses pointing to the target. | [optional] |
| **referring_subnets** | **Integer** | Number of referring subnets pointing to the target. | [optional] |
| **referring_domains_nofollow** | **Integer** | Referring domains linking only with nofollow backlinks (full view). | [optional] |
| **referring_main_domains_nofollow** | **Integer** | Referring root domains linking only with nofollow backlinks (full view). | [optional] |
| **referring_pages_nofollow** | **Integer** | Referring pages linking only with nofollow backlinks (full view). | [optional] |
| **referring_links_tld** | **Hash&lt;String, Integer&gt;** | Referring links grouped by top-level domain of the referring page (full view). | [optional] |
| **referring_links_types** | **Hash&lt;String, Integer&gt;** | Referring links grouped by link type, e.g. anchor, image, redirect (full view). | [optional] |
| **referring_links_attributes** | **Hash&lt;String, Integer&gt;** | Referring links grouped by link attribute, e.g. nofollow, sponsored, ugc (full view). | [optional] |
| **referring_links_platform_types** | **Hash&lt;String, Integer&gt;** | Referring links grouped by platform type, e.g. cms, blogs, ecommerce (full view). | [optional] |
| **referring_links_semantic_locations** | **Hash&lt;String, Integer&gt;** | Referring links grouped by semantic location on the page, e.g. article, footer (full view). | [optional] |
| **referring_links_countries** | **Hash&lt;String, Integer&gt;** | Referring links grouped by country of the referring page (full view). | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksHistoryItem.new(
  date: null,
  new_backlinks: null,
  lost_backlinks: null,
  new_referring_domains: null,
  lost_referring_domains: null,
  crawled_pages: null,
  rank: null,
  backlinks: null,
  backlinks_spam_score: null,
  first_seen: null,
  lost_date: null,
  broken_backlinks: null,
  broken_pages: null,
  referring_domains: null,
  referring_main_domains: null,
  referring_pages: null,
  referring_ips: null,
  referring_subnets: null,
  referring_domains_nofollow: null,
  referring_main_domains_nofollow: null,
  referring_pages_nofollow: null,
  referring_links_tld: null,
  referring_links_types: null,
  referring_links_attributes: null,
  referring_links_platform_types: null,
  referring_links_semantic_locations: null,
  referring_links_countries: null
)
```

