# Unifapi::SeoBacklinksBulkNewLostReferringDomainsItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Domain, subdomain, or page echoed from the request. |  |
| **new_referring_domains** | **Integer** | Referring domains gained since date_from. | [optional] |
| **lost_referring_domains** | **Integer** | Referring domains lost since date_from. | [optional] |
| **new_referring_main_domains** | **Integer** | Referring root domains gained since date_from. | [optional] |
| **lost_referring_main_domains** | **Integer** | Referring root domains lost since date_from. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksBulkNewLostReferringDomainsItem.new(
  target: null,
  new_referring_domains: null,
  lost_referring_domains: null,
  new_referring_main_domains: null,
  lost_referring_main_domains: null
)
```

