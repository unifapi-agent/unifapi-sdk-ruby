# Unifapi::SeoBacklinksBulkBacklinkItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Domain, subdomain, or page echoed from the request. |  |
| **backlinks** | **Integer** | Number of backlinks pointing to the target. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksBulkBacklinkItem.new(
  target: null,
  backlinks: null
)
```

