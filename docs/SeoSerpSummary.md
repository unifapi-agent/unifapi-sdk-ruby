# Unifapi::SeoSerpSummary

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **organic_results** | **Integer** |  |  |
| **billable_results** | **Integer** |  |  |
| **rich_results** | **Integer** |  |  |
| **paid_results** | **Integer** |  |  |
| **feature_counts** | **Hash&lt;String, Integer&gt;** |  |  |
| **target_present** | **Boolean** |  | [optional] |
| **target_best_rank** | **Integer** |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoSerpSummary.new(
  organic_results: null,
  billable_results: null,
  rich_results: null,
  paid_results: null,
  feature_counts: null,
  target_present: null,
  target_best_rank: null
)
```

