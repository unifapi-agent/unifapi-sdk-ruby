# Unifapi::GeoSerpRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **query** | **String** | Search query to inspect in AI Mode. |  |
| **target** | **String** | Optional domain or URL to mark when it appears in AI Mode answers, links, or cited references. | [optional] |
| **location** | [**GeoSerpLocation**](GeoSerpLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |
| **device** | **String** | AI SERP device type. Defaults to desktop. | [optional] |
| **include_pixel_rankings** | **Boolean** | When true, request pixel rectangle data for visual AI SERP analysis. | [optional] |
| **view** | [**GeoSerpView**](GeoSerpView.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::GeoSerpRequest.new(
  query: null,
  target: null,
  location: null,
  language: null,
  device: null,
  include_pixel_rankings: null,
  view: null
)
```

