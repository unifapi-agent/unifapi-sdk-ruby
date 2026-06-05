# Unifapi::SeoSerpResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **query** | **String** |  |  |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **device** | **String** |  |  |
| **os** | [**SeoSerpOs**](SeoSerpOs.md) |  | [optional] |
| **view** | [**SeoSerpView**](SeoSerpView.md) |  |  |
| **rank_window** | [**SeoSerpRankWindow**](SeoSerpRankWindow.md) |  |  |
| **observed_at** | **String** |  | [optional] |
| **search_url** | **String** |  | [optional] |
| **total_results** | **Integer** |  | [optional] |
| **serp_features** | **Array&lt;String&gt;** |  |  |
| **summary** | [**SeoSerpSummary**](SeoSerpSummary.md) |  |  |
| **questions** | [**Array&lt;SeoSerpQuestion&gt;**](SeoSerpQuestion.md) | People Also Ask questions useful for SEO content-gap analysis. |  |
| **results** | [**Array&lt;SeoSerpResult&gt;**](SeoSerpResult.md) | SERP elements returned in source order. Organic results are billable; ads, reviews, people-also-ask, knowledge graph, and other rich elements are returned as free context. |  |
| **target** | [**SeoSerpTarget**](SeoSerpTarget.md) |  | [optional] |
| **competitors** | [**Array&lt;SeoSerpCompetitor&gt;**](SeoSerpCompetitor.md) | Organic result domains excluding the optional target domain. Omitted when results are truncated by balance. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoSerpResponse.new(
  query: null,
  location: null,
  language: null,
  device: null,
  os: null,
  view: null,
  rank_window: null,
  observed_at: null,
  search_url: null,
  total_results: null,
  serp_features: null,
  summary: null,
  questions: null,
  results: null,
  target: null,
  competitors: null
)
```

