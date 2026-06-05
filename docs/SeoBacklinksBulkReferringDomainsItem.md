# Unifapi::SeoBacklinksBulkReferringDomainsItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Domain, subdomain, or page echoed from the request. |  |
| **referring_domains** | **Integer** | Number of referring domains pointing to the target. | [optional] |
| **referring_domains_nofollow** | **Integer** | Referring domains linking only with nofollow backlinks. | [optional] |
| **referring_main_domains** | **Integer** | Number of referring root domains pointing to the target. | [optional] |
| **referring_main_domains_nofollow** | **Integer** | Referring root domains linking only with nofollow backlinks. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksBulkReferringDomainsItem.new(
  target: null,
  referring_domains: null,
  referring_domains_nofollow: null,
  referring_main_domains: null,
  referring_main_domains_nofollow: null
)
```

