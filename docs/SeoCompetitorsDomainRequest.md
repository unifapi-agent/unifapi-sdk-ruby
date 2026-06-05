# Unifapi::SeoCompetitorsDomainRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Target domain, such as example.com or https://example.com. Specified without www. |  |
| **location** | [**SeoCompetitorsDomainLocation**](SeoCompetitorsDomainLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |
| **exclude_top_domains** | **Boolean** | When true, exclude the largest global domains (e.g. wikipedia, amazon) from results. | [optional] |
| **intersecting_domains** | **Array&lt;String&gt;** | Restrict results to competitors that also share keywords with these domains. | [optional] |
| **limit** | **Integer** | Maximum number of competing domains to return. Defaults to 100. | [optional] |
| **offset** | **Integer** | Number of domains to skip from the start of the results. | [optional] |
| **view** | [**SeoDomainMetricsView**](SeoDomainMetricsView.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoCompetitorsDomainRequest.new(
  target: null,
  location: null,
  language: null,
  exclude_top_domains: null,
  intersecting_domains: null,
  limit: null,
  offset: null,
  view: null
)
```

