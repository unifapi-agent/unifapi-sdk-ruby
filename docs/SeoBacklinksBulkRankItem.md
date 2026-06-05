# Unifapi::SeoBacklinksBulkRankItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Domain, subdomain, or page echoed from the request. |  |
| **rank** | **Integer** | Backlink rank of the target (0-1000 by default), similar to PageRank. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksBulkRankItem.new(
  target: null,
  rank: null
)
```

