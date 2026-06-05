# Unifapi::SeoHistoricalSerpsRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **keyword** | **String** | Keyword to retrieve historical SERP snapshots for. |  |
| **location** | [**SeoHistoricalSerpsLocation**](SeoHistoricalSerpsLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |
| **date_from** | **String** | Start of the history window. Date in yyyy-mm-dd format. Minimum date: 2019-01-01. | [optional] |
| **date_to** | **String** | End of the history window. Date in yyyy-mm-dd format. Minimum date: 2019-01-01. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoHistoricalSerpsRequest.new(
  keyword: null,
  location: null,
  language: null,
  date_from: null,
  date_to: null
)
```

