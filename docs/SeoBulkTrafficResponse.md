# Unifapi::SeoBulkTrafficResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **view** | [**SeoDomainMetricsView**](SeoDomainMetricsView.md) |  |  |
| **results** | [**Array&lt;SeoBulkTrafficItem&gt;**](SeoBulkTrafficItem.md) | Estimated traffic per requested domain. Each domain is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBulkTrafficResponse.new(
  location: null,
  language: null,
  view: null,
  results: null
)
```

