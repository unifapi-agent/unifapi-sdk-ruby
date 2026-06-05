# Unifapi::SeoHistoricalRankItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **year** | **Integer** | Year of the metrics snapshot. |  |
| **month** | **Integer** | Month of the metrics snapshot (1-12). | [optional] |
| **organic** | [**SeoDomainMetricGroup**](SeoDomainMetricGroup.md) |  | [optional] |
| **paid** | [**SeoDomainMetricsPaid**](SeoDomainMetricsPaid.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoHistoricalRankItem.new(
  year: null,
  month: null,
  organic: null,
  paid: null
)
```

