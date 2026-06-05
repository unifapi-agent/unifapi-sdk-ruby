# Unifapi::GeoMentionsTopPagesResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **engine** | [**GeoEngine**](GeoEngine.md) |  |  |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **totals** | [**GeoMentionBreakdown**](GeoMentionBreakdown.md) |  | [optional] |
| **results** | [**Array&lt;GeoMentionItem&gt;**](GeoMentionItem.md) | Top cited pages, one billable record each, with per-dimension breakdowns. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::GeoMentionsTopPagesResponse.new(
  engine: null,
  location: null,
  language: null,
  totals: null,
  results: null
)
```

