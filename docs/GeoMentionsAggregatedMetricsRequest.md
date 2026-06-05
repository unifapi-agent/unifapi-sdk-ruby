# Unifapi::GeoMentionsAggregatedMetricsRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | [**Array&lt;GeoMentionsTarget&gt;**](GeoMentionsTarget.md) | Up to 10 target entities, each a domain or a keyword. |  |
| **engine** | [**GeoEngine**](GeoEngine.md) |  | [optional] |
| **location** | [**GeoKeywordSearchVolumeRequestLocation**](GeoKeywordSearchVolumeRequestLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |
| **filters** | [**GeoMentionsAggregatedMetricsRequestFilters**](GeoMentionsAggregatedMetricsRequestFilters.md) |  | [optional] |
| **internal_list_limit** | **Integer** | Max elements per internal grouped array (source/search-result domains). Default 10. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::GeoMentionsAggregatedMetricsRequest.new(
  target: null,
  engine: null,
  location: null,
  language: null,
  filters: null,
  internal_list_limit: null
)
```

