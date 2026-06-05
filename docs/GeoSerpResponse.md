# Unifapi::GeoSerpResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **query** | **String** |  |  |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **device** | **String** |  |  |
| **surface** | **String** |  |  |
| **view** | [**GeoSerpView**](GeoSerpView.md) |  |  |
| **observed_at** | **String** |  | [optional] |
| **search_url** | **String** |  | [optional] |
| **total_results** | **Integer** |  | [optional] |
| **serp_features** | **Array&lt;String&gt;** |  |  |
| **results** | [**Array&lt;GeoSerpResult&gt;**](GeoSerpResult.md) | AI SERP elements returned in source order. Top-level AI overview records are billable; cited references, links, images, and answer sections are returned as context inside each result. |  |
| **target** | [**GeoSerpTarget**](GeoSerpTarget.md) |  | [optional] |
| **competitors** | [**Array&lt;GeoSerpCompetitor&gt;**](GeoSerpCompetitor.md) | Domains cited or linked by AI Mode, excluding the optional target domain. Omitted when results are truncated by balance. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::GeoSerpResponse.new(
  query: null,
  location: null,
  language: null,
  device: null,
  surface: null,
  view: null,
  observed_at: null,
  search_url: null,
  total_results: null,
  serp_features: null,
  results: null,
  target: null,
  competitors: null
)
```

