# Unifapi::SeoSerpCompetitorItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **domain** | **String** | Competing domain ranking for the seed keywords. |  |
| **avg_position** | **Float** | Average position of the domain across the seed keywords. | [optional] |
| **median_position** | **Float** | Median position of the domain across the seed keywords. | [optional] |
| **rating** | **Float** | Relative visibility score weighing positions and search volume. | [optional] |
| **etv** | **Float** | Estimated monthly organic traffic the domain gets from the seed keywords. | [optional] |
| **keywords_count** | **Integer** | Number of seed keywords the domain ranks for. | [optional] |
| **visibility** | **Float** | Share of the seed keywords&#39; total traffic captured by the domain. | [optional] |
| **relevant_serp_items** | **Integer** | Number of SERP elements the domain owns across the seed keywords. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoSerpCompetitorItem.new(
  domain: null,
  avg_position: null,
  median_position: null,
  rating: null,
  etv: null,
  keywords_count: null,
  visibility: null,
  relevant_serp_items: null
)
```

