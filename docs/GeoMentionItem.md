# Unifapi::GeoMentionItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **key** | **String** | Domain, page URL, or aggregation label this row summarizes. |  |
| **mentions** | **Float** | Total LLM mentions for this row, summed across platforms. | [optional] |
| **breakdown** | [**GeoMentionBreakdown**](GeoMentionBreakdown.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::GeoMentionItem.new(
  key: null,
  mentions: null,
  breakdown: null
)
```

