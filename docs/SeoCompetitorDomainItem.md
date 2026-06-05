# Unifapi::SeoCompetitorDomainItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **domain** | **String** | Competing domain that shares keywords with the target. |  |
| **avg_position** | **Float** | Average position of the competitor across the shared keywords. | [optional] |
| **sum_position** | **Integer** | Sum of the competitor&#39;s positions across the shared keywords. | [optional] |
| **intersections** | **Integer** | Number of keywords both the target and this competitor rank for. | [optional] |
| **metrics** | [**SeoCompetitorDomainItemMetrics**](SeoCompetitorDomainItemMetrics.md) |  | [optional] |
| **full_domain_metrics** | [**SeoCompetitorDomainItemFullDomainMetrics**](SeoCompetitorDomainItemFullDomainMetrics.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoCompetitorDomainItem.new(
  domain: null,
  avg_position: null,
  sum_position: null,
  intersections: null,
  metrics: null,
  full_domain_metrics: null
)
```

