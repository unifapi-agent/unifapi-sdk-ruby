# Unifapi::SeoSubdomainsResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Target domain echoed from the request. |  |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **view** | [**SeoDomainMetricsView**](SeoDomainMetricsView.md) |  |  |
| **total_count** | **Integer** | Total number of subdomains available for the target. | [optional] |
| **results** | [**Array&lt;SeoSubdomainItem&gt;**](SeoSubdomainItem.md) | Subdomains of the target with ranking and traffic metrics. Each subdomain is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoSubdomainsResponse.new(
  target: null,
  location: null,
  language: null,
  view: null,
  total_count: null,
  results: null
)
```

