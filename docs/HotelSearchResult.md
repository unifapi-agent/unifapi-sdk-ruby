# Unifapi::HotelSearchResult

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **hotel_identifier** | **String** | Unique hotel id. Pass it to /hotels/info for full details. | [optional] |
| **title** | **String** | Hotel or vacation rental name. | [optional] |
| **stars** | **Integer** | Hotel class rating, 1-5. | [optional] |
| **is_paid** | **Boolean** | True for paid hotel listings. | [optional] |
| **location** | [**HotelSearchGeo**](HotelSearchGeo.md) |  | [optional] |
| **reviews** | [**HotelSearchResultReviews**](HotelSearchResultReviews.md) |  | [optional] |
| **prices** | [**HotelSearchResultPrices**](HotelSearchResultPrices.md) |  | [optional] |
| **overview_images** | **Array&lt;String&gt;** | Preview image URLs for the hotel when present. | [optional] |
| **is_billable** | **Boolean** | Each hotel listing is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::HotelSearchResult.new(
  hotel_identifier: null,
  title: null,
  stars: null,
  is_paid: null,
  location: null,
  reviews: null,
  prices: null,
  overview_images: null,
  is_billable: null
)
```

