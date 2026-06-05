# Unifapi::SeoHistoricalMetricPeriod

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **year** | **Integer** | Year of the metrics snapshot. |  |
| **month** | **Integer** | Month of the metrics snapshot (1-12). | [optional] |
| **etv** | **Float** | Estimated organic traffic (clicks) in this period. | [optional] |
| **count** | **Integer** | Number of ranking keywords in this period. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoHistoricalMetricPeriod.new(
  year: null,
  month: null,
  etv: null,
  count: null
)
```

