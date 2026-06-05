# Unifapi::SeoHistoricalRankOverviewRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Target domain, such as example.com or https://example.com. Specified without www. |  |
| **location** | [**SeoHistoricalRankOverviewLocation**](SeoHistoricalRankOverviewLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |
| **date_from** | **String** | Start of the history window. Date in yyyy-mm-dd format. Minimum date: 2019-01-01. | [optional] |
| **date_to** | **String** | End of the history window. Date in yyyy-mm-dd format. Minimum date: 2019-01-01. | [optional] |
| **view** | [**SeoDomainMetricsView**](SeoDomainMetricsView.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoHistoricalRankOverviewRequest.new(
  target: null,
  location: null,
  language: null,
  date_from: null,
  date_to: null,
  view: null
)
```

