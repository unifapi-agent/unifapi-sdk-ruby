# Unifapi::SeoRelevantPagesResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Target domain echoed from the request. |  |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **view** | [**SeoDomainMetricsView**](SeoDomainMetricsView.md) |  |  |
| **total_count** | **Integer** | Total number of ranking pages available for the target. | [optional] |
| **results** | [**Array&lt;SeoRelevantPageItem&gt;**](SeoRelevantPageItem.md) | Pages of the target ranked by traffic, each with ranking metrics. Each page is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoRelevantPagesResponse.new(
  target: null,
  location: null,
  language: null,
  view: null,
  total_count: null,
  results: null
)
```

