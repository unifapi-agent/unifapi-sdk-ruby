# Unifapi::SeoHistoricalSerpItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **datetime** | **String** | When this SERP snapshot was collected (ISO 8601). |  |
| **se_results_count** | **Integer** | Number of organic results Google reported for the keyword at this time. | [optional] |
| **items_count** | **Integer** | Number of SERP elements captured in this snapshot. | [optional] |
| **item_types** | **Array&lt;String&gt;** | SERP feature types present in this snapshot (organic, paid, featured_snippet, etc.). | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoHistoricalSerpItem.new(
  datetime: null,
  se_results_count: null,
  items_count: null,
  item_types: null
)
```

