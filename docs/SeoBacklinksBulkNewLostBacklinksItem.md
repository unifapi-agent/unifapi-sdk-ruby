# Unifapi::SeoBacklinksBulkNewLostBacklinksItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Domain, subdomain, or page echoed from the request. |  |
| **new_backlinks** | **Integer** | Number of new backlinks gained since date_from. | [optional] |
| **lost_backlinks** | **Integer** | Number of backlinks lost since date_from. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksBulkNewLostBacklinksItem.new(
  target: null,
  new_backlinks: null,
  lost_backlinks: null
)
```

