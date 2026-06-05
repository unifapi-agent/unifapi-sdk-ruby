# Unifapi::SeoRelatedKeywordItem

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
| **depth** | **Integer** | Search depth at which this keyword was found, relative to the seed keyword. | [optional] |
| **related_keywords** | **Array&lt;String&gt;** | Keywords from the &#39;searches related to&#39; SERP element for this keyword. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoRelatedKeywordItem.new(
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
  depth: null,
  related_keywords: null
)
```

