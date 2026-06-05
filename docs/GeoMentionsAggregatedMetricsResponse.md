# Unifapi::GeoMentionsAggregatedMetricsResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **engine** | [**GeoEngine**](GeoEngine.md) |  |  |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **totals** | [**GeoMentionBreakdown**](GeoMentionBreakdown.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::GeoMentionsAggregatedMetricsResponse.new(
  engine: null,
  location: null,
  language: null,
  totals: null
)
```

