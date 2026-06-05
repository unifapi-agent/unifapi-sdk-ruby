# Unifapi::GeoKeywordSearchVolumeRecord

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **keyword** | **String** |  |  |
| **ai_search_volume** | **Float** |  | [optional] |
| **monthly_searches** | [**Array&lt;GeoMonthlySearch&gt;**](GeoMonthlySearch.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::GeoKeywordSearchVolumeRecord.new(
  keyword: null,
  ai_search_volume: null,
  monthly_searches: null
)
```

