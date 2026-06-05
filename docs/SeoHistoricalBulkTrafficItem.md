# Unifapi::SeoHistoricalBulkTrafficItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Domain echoed from the request. |  |
| **organic** | [**Array&lt;SeoHistoricalMetricPeriod&gt;**](SeoHistoricalMetricPeriod.md) | Organic traffic time series. | [optional] |
| **paid** | [**Array&lt;SeoHistoricalMetricPeriod&gt;**](SeoHistoricalMetricPeriod.md) | Paid traffic time series. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoHistoricalBulkTrafficItem.new(
  target: null,
  organic: null,
  paid: null
)
```

