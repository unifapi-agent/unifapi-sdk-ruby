# Unifapi::GeoMentionsTopPagesRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | [**Array&lt;GeoMentionsTarget&gt;**](GeoMentionsTarget.md) | Up to 10 target entities, each a domain or a keyword. |  |
| **engine** | [**GeoEngine**](GeoEngine.md) |  | [optional] |
| **location** | [**GeoKeywordSearchVolumeRequestLocation**](GeoKeywordSearchVolumeRequestLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |
| **links_scope** | **String** | Which links to extract pages from. Defaults to sources. | [optional] |
| **filters** | [**GeoMentionsAggregatedMetricsRequestFilters**](GeoMentionsAggregatedMetricsRequestFilters.md) |  | [optional] |
| **items_list_limit** | **Integer** | Max number of top pages to return. Default 5. | [optional] |
| **internal_list_limit** | **Integer** | Max elements per internal grouped array. Default 5. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::GeoMentionsTopPagesRequest.new(
  target: null,
  engine: null,
  location: null,
  language: null,
  links_scope: null,
  filters: null,
  items_list_limit: null,
  internal_list_limit: null
)
```

