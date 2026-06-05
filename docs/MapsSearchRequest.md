# Unifapi::MapsSearchRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **query** | **String** | Search query to inspect. |  |
| **location** | [**SerpListLocation**](SerpListLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |
| **limit** | **Integer** | Number of results to return, matching the limit parameter used across other UnifAPI endpoints. Maps to result depth. | [optional] |
| **view** | [**SerpListView**](SerpListView.md) |  | [optional] |
| **device** | [**SerpListDevice**](SerpListDevice.md) |  | [optional] |
| **os** | [**SerpListOs**](SerpListOs.md) |  | [optional] |
| **search_this_area** | **Boolean** | When true, return results from the displayed map area rather than the broader location. | [optional] |
| **search_places** | **Boolean** | When true, use search-places mode to return listings the way the mobile app surfaces them. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::MapsSearchRequest.new(
  query: null,
  location: null,
  language: null,
  limit: null,
  view: null,
  device: null,
  os: null,
  search_this_area: null,
  search_places: null
)
```

