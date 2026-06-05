# Unifapi::SeoHistoricalSerpsResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **keyword** | **String** | Keyword echoed from the request. |  |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **results** | [**Array&lt;SeoHistoricalSerpItem&gt;**](SeoHistoricalSerpItem.md) | SERP composition snapshots for the keyword over time. Each snapshot is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoHistoricalSerpsResponse.new(
  keyword: null,
  location: null,
  language: null,
  results: null
)
```

