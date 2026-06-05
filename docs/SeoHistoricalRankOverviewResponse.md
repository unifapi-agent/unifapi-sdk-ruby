# Unifapi::SeoHistoricalRankOverviewResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Target domain echoed from the request. |  |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **view** | [**SeoDomainMetricsView**](SeoDomainMetricsView.md) |  |  |
| **results** | [**Array&lt;SeoHistoricalRankItem&gt;**](SeoHistoricalRankItem.md) | Monthly ranking distribution and traffic for the target over time. Each month is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoHistoricalRankOverviewResponse.new(
  target: null,
  location: null,
  language: null,
  view: null,
  results: null
)
```

