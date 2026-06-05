# Unifapi::GeoMentionsSearchResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **engine** | [**GeoEngine**](GeoEngine.md) |  |  |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **total_count** | **Integer** | Total mentions matching the request. | [optional] |
| **returned_count** | **Integer** | Mentions returned in results. |  |
| **cursor** | **String** | search_after_token for the next page, when more remain. | [optional] |
| **results** | [**Array&lt;GeoMentionRecord&gt;**](GeoMentionRecord.md) | One billable record per matched mention. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::GeoMentionsSearchResponse.new(
  engine: null,
  location: null,
  language: null,
  total_count: null,
  returned_count: null,
  cursor: null,
  results: null
)
```

