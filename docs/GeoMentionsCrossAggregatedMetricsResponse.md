# Unifapi::GeoMentionsCrossAggregatedMetricsResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **engine** | [**GeoEngine**](GeoEngine.md) |  |  |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **totals** | [**GeoMentionBreakdown**](GeoMentionBreakdown.md) |  | [optional] |
| **results** | [**Array&lt;GeoMentionItem&gt;**](GeoMentionItem.md) | One billable record per labeled group, with its mention breakdown. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::GeoMentionsCrossAggregatedMetricsResponse.new(
  engine: null,
  location: null,
  language: null,
  totals: null,
  results: null
)
```

