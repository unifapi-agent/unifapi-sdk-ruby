# Unifapi::GeoMentionRecord

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **engine** | [**GeoEngine**](GeoEngine.md) |  | [optional] |
| **model** | **String** |  | [optional] |
| **question** | **String** |  | [optional] |
| **answer** | **String** | Model answer in markdown. Included for standard and full views. | [optional] |
| **ai_search_volume** | **Float** |  | [optional] |
| **monthly_searches** | [**Array&lt;GeoMentionMonthly&gt;**](GeoMentionMonthly.md) |  | [optional] |
| **sources** | [**Array&lt;GeoMentionSource&gt;**](GeoMentionSource.md) |  | [optional] |
| **search_results** | [**Array&lt;GeoMentionSearchResult&gt;**](GeoMentionSearchResult.md) |  | [optional] |
| **brand_entities** | [**Array&lt;GeoMentionBrandEntity&gt;**](GeoMentionBrandEntity.md) |  | [optional] |
| **fan_out_queries** | **Array&lt;String&gt;** |  | [optional] |
| **first_response_at** | **String** |  | [optional] |
| **last_response_at** | **String** |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::GeoMentionRecord.new(
  engine: null,
  model: null,
  question: null,
  answer: null,
  ai_search_volume: null,
  monthly_searches: null,
  sources: null,
  search_results: null,
  brand_entities: null,
  fan_out_queries: null,
  first_response_at: null,
  last_response_at: null
)
```

