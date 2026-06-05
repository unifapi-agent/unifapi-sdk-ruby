# Unifapi::GeoMentionsCrossAggregatedMetricsRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **groups** | [**Array&lt;GeoMentionsCrossGroup&gt;**](GeoMentionsCrossGroup.md) | Labeled target groups to compare against each other. |  |
| **engine** | [**GeoEngine**](GeoEngine.md) |  | [optional] |
| **location** | [**GeoKeywordSearchVolumeRequestLocation**](GeoKeywordSearchVolumeRequestLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |
| **filters** | [**GeoMentionsAggregatedMetricsRequestFilters**](GeoMentionsAggregatedMetricsRequestFilters.md) |  | [optional] |
| **internal_list_limit** | **Integer** | Max elements per internal grouped array. Default 5. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::GeoMentionsCrossAggregatedMetricsRequest.new(
  groups: null,
  engine: null,
  location: null,
  language: null,
  filters: null,
  internal_list_limit: null
)
```

