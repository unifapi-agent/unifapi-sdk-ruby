# Unifapi::LocalFinderRequest

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
| **min_rating** | **Float** | Filter results to places with at least this average rating. | [optional] |
| **time_filter** | **String** | Filter results by open hours. open_now keeps only places open at request time. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::LocalFinderRequest.new(
  query: null,
  location: null,
  language: null,
  limit: null,
  view: null,
  device: null,
  os: null,
  min_rating: null,
  time_filter: null
)
```

