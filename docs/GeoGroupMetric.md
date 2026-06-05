# Unifapi::GeoGroupMetric

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **value** | **String** | The group this row aggregates, e.g. a platform, location, or domain. |  |
| **type** | **String** | Dimension the value belongs to when DataForSEO labels it, e.g. platform or location. | [optional] |
| **mentions** | **Float** | LLM mentions counted for this group. | [optional] |
| **ai_search_volume** | **Float** | AI search volume attributed to this group. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::GeoGroupMetric.new(
  value: null,
  type: null,
  mentions: null,
  ai_search_volume: null
)
```

