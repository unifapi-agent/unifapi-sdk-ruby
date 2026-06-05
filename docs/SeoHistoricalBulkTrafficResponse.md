# Unifapi::SeoHistoricalBulkTrafficResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **results** | [**Array&lt;SeoHistoricalBulkTrafficItem&gt;**](SeoHistoricalBulkTrafficItem.md) | Monthly estimated traffic time series per requested domain. Each domain is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoHistoricalBulkTrafficResponse.new(
  location: null,
  language: null,
  results: null
)
```

