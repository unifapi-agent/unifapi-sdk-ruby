# Unifapi::SeoBacklinksTimeseriesResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Target echoed from the request. |  |
| **group_range** | **String** | Granularity used to group the series. | [optional] |
| **date_from** | **String** | Start date of the series echoed from the request. | [optional] |
| **date_to** | **String** | End date of the series echoed from the request. | [optional] |
| **series** | [**Array&lt;SeoBacklinksTimeseriesItem&gt;**](SeoBacklinksTimeseriesItem.md) | Backlink metrics grouped by period, oldest to newest. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksTimeseriesResponse.new(
  target: null,
  group_range: null,
  date_from: null,
  date_to: null,
  series: null
)
```

