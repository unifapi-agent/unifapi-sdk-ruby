# Unifapi::SeoBulkTrafficItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Domain echoed from the request. |  |
| **metrics** | [**SeoDomainMetrics**](SeoDomainMetrics.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBulkTrafficItem.new(
  target: null,
  metrics: null
)
```

