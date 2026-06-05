# Unifapi::SeoSerpRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **query** | **String** | Search query to inspect. |  |
| **target** | **String** | Optional domain or URL to mark in the results, such as example.com or https://example.com/page. | [optional] |
| **location** | [**SeoSerpLocation**](SeoSerpLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |
| **device** | **String** | SERP device type. Defaults to desktop. | [optional] |
| **os** | [**SeoSerpOs**](SeoSerpOs.md) |  | [optional] |
| **page** | **Integer** | 1-based Google result page to start from. Defaults to 1. Implemented with Google&#39;s start parameter and ranks are adjusted to global SERP positions. | [optional] |
| **depth** | **Integer** | Organic result depth to crawl from the requested page. Defaults to 10. DataForSEO bills source in 10-result pages; UnifAPI bills returned billable organic records. | [optional] |
| **limit** | **Integer** | Number of organic results to return, matching the limit parameter used across other UnifAPI endpoints. Maps to DataForSEO depth and is used only when depth is omitted; defaults to 10. | [optional] |
| **view** | [**SeoSerpView**](SeoSerpView.md) |  | [optional] |
| **include_ai_overview** | **Boolean** | When true, ask DataForSEO to load asynchronous Google AI Overview blocks in the organic SERP when available. This can add source cost. | [optional] |
| **people_also_ask_depth** | **Integer** | Optional click depth for People Also Ask expansion. Useful for SEO content-gap research and can add source cost. | [optional] |
| **include_pixel_rankings** | **Boolean** | When true, request pixel rectangle data for above-the-fold and visual rank analysis. This can add source cost. | [optional] |
| **viewport** | [**SeoSerpViewport**](SeoSerpViewport.md) |  | [optional] |
| **google_domain** | **String** | Optional Google domain override such as google.co.uk or google.de. | [optional] |
| **google_search_params** | **String** | Advanced Google search URL parameters such as nfpr&#x3D;1. Prefer typed fields like page and include_omitted_results when available. | [optional] |
| **include_omitted_results** | **Boolean** | When true, adds filter&#x3D;0 to inspect Google results that may otherwise be omitted. Useful for deep rank checks. | [optional] |
| **remove_url_params** | **Array&lt;String&gt;** | URL query parameters to remove from result URLs before matching, such as srsltid. | [optional] |
| **expand_related_results** | **Boolean** | When true, return related/sitelink-style organic results as separate organic elements instead of nesting them. | [optional] |
| **stop_at_target** | **Boolean** | When true and target is provided, stop crawling once the target is found. Useful for cheaper deep-rank checks, but later competitors may be omitted. | [optional] |
| **target_match** | [**SeoSerpTargetMatch**](SeoSerpTargetMatch.md) |  | [optional] |
| **target_search_mode** | [**SeoSerpTargetSearchMode**](SeoSerpTargetSearchMode.md) |  | [optional] |
| **target_element_types** | [**Array&lt;SeoSerpTargetElementType&gt;**](SeoSerpTargetElementType.md) | SERP element types to inspect for stop_at_target matches. Defaults to all first-level URL/domain elements. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoSerpRequest.new(
  query: null,
  target: null,
  location: null,
  language: null,
  device: null,
  os: null,
  page: null,
  depth: null,
  limit: null,
  view: null,
  include_ai_overview: null,
  people_also_ask_depth: null,
  include_pixel_rankings: null,
  viewport: null,
  google_domain: null,
  google_search_params: null,
  include_omitted_results: null,
  remove_url_params: null,
  expand_related_results: null,
  stop_at_target: null,
  target_match: null,
  target_search_mode: null,
  target_element_types: null
)
```

