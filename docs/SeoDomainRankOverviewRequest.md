# Unifapi::SeoDomainRankOverviewRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Target domain, such as example.com or https://example.com. Specified without www. |  |
| **location** | [**SeoDomainRankOverviewLocation**](SeoDomainRankOverviewLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |
| **view** | [**SeoDomainMetricsView**](SeoDomainMetricsView.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoDomainRankOverviewRequest.new(
  target: null,
  location: null,
  language: null,
  view: null
)
```

