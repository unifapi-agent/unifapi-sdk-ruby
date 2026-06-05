# Unifapi::SeoBacklinksTimeseriesNewLostResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Target echoed from the request. |  |
| **group_range** | **String** | Granularity used to group the series. | [optional] |
| **date_from** | **String** | Start date of the series echoed from the request. | [optional] |
| **date_to** | **String** | End date of the series echoed from the request. | [optional] |
| **series** | [**Array&lt;SeoBacklinksTimeseriesNewLostItem&gt;**](SeoBacklinksTimeseriesNewLostItem.md) | New/lost backlink and referring-domain counts grouped by period, oldest to newest. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksTimeseriesNewLostResponse.new(
  target: null,
  group_range: null,
  date_from: null,
  date_to: null,
  series: null
)
```

