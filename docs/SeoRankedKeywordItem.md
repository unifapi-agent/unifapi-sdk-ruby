# Unifapi::SeoRankedKeywordItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **keyword** | **String** | Keyword phrase. |  |
| **search_volume** | **Integer** | Average monthly Google search volume. | [optional] |
| **cpc** | **Float** | Average cost-per-click in USD. | [optional] |
| **competition** | **Float** | Google Ads competition index between 0 and 1. | [optional] |
| **competition_level** | **String** | Google Ads competition level: LOW, MEDIUM, or HIGH. | [optional] |
| **keyword_difficulty** | **Integer** | Relative difficulty of ranking in the top-10 organic results, 0-100. | [optional] |
| **search_intent** | **String** | Main search intent: informational, navigational, commercial, or transactional. | [optional] |
| **search_intent_alternatives** | **Array&lt;String&gt;** | Supplementary search intents detected for the keyword. | [optional] |
| **low_top_of_page_bid** | **Float** | Lower-range top-of-page bid in USD from Google Ads. | [optional] |
| **high_top_of_page_bid** | **Float** | Upper-range top-of-page bid in USD from Google Ads. | [optional] |
| **words_count** | **Integer** | Number of words in the keyword. | [optional] |
| **detected_language** | **String** | Language detected for the keyword. | [optional] |
| **search_volume_trend** | [**SeoKeywordSearchVolumeTrend**](SeoKeywordSearchVolumeTrend.md) |  | [optional] |
| **serp_item_types** | **Array&lt;String&gt;** | SERP feature types present for the keyword (only with include_serp_info). | [optional] |
| **serp_results_count** | **Integer** | Number of organic results Google reports for the keyword. | [optional] |
| **monthly_searches** | [**Array&lt;SeoKeywordMonthlySearch&gt;**](SeoKeywordMonthlySearch.md) | Per-month search volume for the past 12 months (full view only). | [optional] |
| **last_updated_at** | **String** | When DataForSEO last refreshed the keyword metrics. | [optional] |
| **rank_group** | **Integer** | Position in SERP grouping organic results together (ignores ads/features). | [optional] |
| **rank_absolute** | **Integer** | Absolute position in SERP counting every element. | [optional] |
| **position** | **String** | Side of the SERP the element appears on: left or right. | [optional] |
| **domain** | **String** | Domain that holds the ranking page. | [optional] |
| **title** | **String** | Title of the ranking page. | [optional] |
| **url** | **String** | URL of the ranking page. | [optional] |
| **etv** | **Float** | Estimated monthly traffic the keyword sends to this URL. | [optional] |
| **estimated_paid_traffic_cost** | **Float** | Estimated monthly ad cost (USD) of the traffic this URL receives. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoRankedKeywordItem.new(
  keyword: null,
  search_volume: null,
  cpc: null,
  competition: null,
  competition_level: null,
  keyword_difficulty: null,
  search_intent: null,
  search_intent_alternatives: null,
  low_top_of_page_bid: null,
  high_top_of_page_bid: null,
  words_count: null,
  detected_language: null,
  search_volume_trend: null,
  serp_item_types: null,
  serp_results_count: null,
  monthly_searches: null,
  last_updated_at: null,
  rank_group: null,
  rank_absolute: null,
  position: null,
  domain: null,
  title: null,
  url: null,
  etv: null,
  estimated_paid_traffic_cost: null
)
```

