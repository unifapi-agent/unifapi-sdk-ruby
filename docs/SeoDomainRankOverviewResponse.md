# Unifapi::SeoDomainRankOverviewResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Target domain echoed from the request. |  |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **view** | [**SeoDomainMetricsView**](SeoDomainMetricsView.md) |  |  |
| **results** | [**Array&lt;SeoDomainMetrics&gt;**](SeoDomainMetrics.md) | Ranking distribution and estimated traffic for the target domain. One billable record per location/language overview. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoDomainRankOverviewResponse.new(
  target: null,
  location: null,
  language: null,
  view: null,
  results: null
)
```

