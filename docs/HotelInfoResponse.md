# Unifapi::HotelInfoResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **hotel_identifier** | **String** |  |  |
| **location** | **String** | Search location echoed from the request. |  |
| **language** | **String** |  |  |
| **observed_at** | **String** |  | [optional] |
| **search_url** | **String** |  | [optional] |
| **title** | **String** |  | [optional] |
| **stars** | **Integer** | Hotel class rating, 1-5. | [optional] |
| **stars_description** | **String** |  | [optional] |
| **address** | **String** |  | [optional] |
| **phone** | **String** |  | [optional] |
| **about** | [**HotelAbout**](HotelAbout.md) |  | [optional] |
| **place** | [**HotelPlace**](HotelPlace.md) |  | [optional] |
| **reviews** | [**HotelReviews**](HotelReviews.md) |  | [optional] |
| **overview_images** | **Array&lt;String&gt;** |  | [optional] |
| **prices** | [**HotelPrice**](HotelPrice.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::HotelInfoResponse.new(
  hotel_identifier: null,
  location: null,
  language: null,
  observed_at: null,
  search_url: null,
  title: null,
  stars: null,
  stars_description: null,
  address: null,
  phone: null,
  about: null,
  place: null,
  reviews: null,
  overview_images: null,
  prices: null
)
```

