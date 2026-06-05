# Unifapi::GeoMentionsSearchRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | [**Array&lt;GeoMentionsTarget&gt;**](GeoMentionsTarget.md) | Up to 10 target entities, each a domain or a keyword. |  |
| **engine** | [**GeoEngine**](GeoEngine.md) |  | [optional] |
| **location** | [**GeoKeywordSearchVolumeRequestLocation**](GeoKeywordSearchVolumeRequestLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |
| **filters** | [**GeoMentionsSearchRequestFilters**](GeoMentionsSearchRequestFilters.md) |  | [optional] |
| **order_by** | [**Array&lt;DataForSeoOrderByRule&gt;**](DataForSeoOrderByRule.md) | Sort the matched mentions. Each rule is {\&quot;field\&quot;,\&quot;dir\&quot;} with dir asc or desc; up to 3 rules, applied in order. Sortable fields: ai_search_volume, platform, model. | [optional] |
| **limit** | **Integer** | Max mentions to return. Default 100. | [optional] |
| **offset** | **Integer** | Mentions to skip. Use cursor beyond 9000. | [optional] |
| **cursor** | **String** | search_after_token from a previous response, for deep pagination. | [optional] |
| **view** | [**GeoView**](GeoView.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::GeoMentionsSearchRequest.new(
  target: null,
  engine: null,
  location: null,
  language: null,
  filters: null,
  order_by: null,
  limit: null,
  offset: null,
  cursor: null,
  view: null
)
```

