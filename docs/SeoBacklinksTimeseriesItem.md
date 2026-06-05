# Unifapi::SeoBacklinksTimeseriesItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **date** | **String** | Last day of the grouped period. |  |
| **rank** | **Integer** | Backlink rank of the target at the period end. | [optional] |
| **backlinks** | **Integer** | Backlinks pointing to the target. | [optional] |
| **backlinks_nofollow** | **Integer** | Nofollow backlinks pointing to the target. | [optional] |
| **referring_pages** | **Integer** | Referring pages pointing to the target. | [optional] |
| **referring_pages_nofollow** | **Integer** | Referring pages linking only with nofollow backlinks. | [optional] |
| **referring_domains** | **Integer** | Referring domains pointing to the target. | [optional] |
| **referring_domains_nofollow** | **Integer** | Referring domains linking only with nofollow backlinks. | [optional] |
| **referring_main_domains** | **Integer** | Referring root domains pointing to the target. | [optional] |
| **referring_main_domains_nofollow** | **Integer** | Referring root domains linking only with nofollow backlinks. | [optional] |
| **referring_ips** | **Integer** | Referring IP addresses pointing to the target. | [optional] |
| **referring_subnets** | **Integer** | Referring subnets pointing to the target. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksTimeseriesItem.new(
  date: null,
  rank: null,
  backlinks: null,
  backlinks_nofollow: null,
  referring_pages: null,
  referring_pages_nofollow: null,
  referring_domains: null,
  referring_domains_nofollow: null,
  referring_main_domains: null,
  referring_main_domains_nofollow: null,
  referring_ips: null,
  referring_subnets: null
)
```

