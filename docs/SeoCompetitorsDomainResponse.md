# Unifapi::SeoCompetitorsDomainResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Target domain echoed from the request. |  |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **view** | [**SeoDomainMetricsView**](SeoDomainMetricsView.md) |  |  |
| **total_count** | **Integer** | Total number of competing domains available in DataForSEO&#39;s database. | [optional] |
| **results** | [**Array&lt;SeoCompetitorDomainItem&gt;**](SeoCompetitorDomainItem.md) | Domains competing with the target, with shared-keyword counts and traffic metrics. Each domain is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoCompetitorsDomainResponse.new(
  target: null,
  location: null,
  language: null,
  view: null,
  total_count: null,
  results: null
)
```

