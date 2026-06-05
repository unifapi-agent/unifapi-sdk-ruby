# Unifapi::HotelPlace

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **neighborhood** | **String** | Neighborhood where the hotel is located. | [optional] |
| **neighborhood_description** | **String** |  | [optional] |
| **maps_url** | **String** | Google Maps URL for the hotel location. | [optional] |
| **overall_score** | **Float** | Overall location score from 1 to 5. | [optional] |
| **score_by_categories** | **Hash&lt;String, Float&gt;** | Location sub-scores by category, such as transit or things_to_do. | [optional] |
| **latitude** | **Float** | Latitude of the hotel on Google Maps. | [optional] |
| **longitude** | **Float** | Longitude of the hotel on Google Maps. | [optional] |
| **extras** | **Hash** |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::HotelPlace.new(
  neighborhood: null,
  neighborhood_description: null,
  maps_url: null,
  overall_score: null,
  score_by_categories: null,
  latitude: null,
  longitude: null,
  extras: null
)
```

