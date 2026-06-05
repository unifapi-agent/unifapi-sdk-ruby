# Unifapi::HotelSearchRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **query** | **String** | Optional hotel name or search query. Combine with location to scope the search. | [optional] |
| **location** | [**HotelSearchLocation**](HotelSearchLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |
| **limit** | **Integer** | Number of hotels to return. Defaults to 10. | [optional] |
| **check_in** | **String** | Check-in date. Date in YYYY-MM-DD format. | [optional] |
| **check_out** | **String** | Check-out date. Date in YYYY-MM-DD format. | [optional] |
| **currency** | **String** | ISO 4217 currency code for prices, such as USD. | [optional] |
| **adults** | **Integer** | Number of adult guests. | [optional] |
| **children** | **Array&lt;Integer&gt;** | Ages of children staying, used to refine availability and pricing. | [optional] |
| **stars** | **Array&lt;Integer&gt;** | Filter to hotels with these class ratings, such as [4, 5]. | [optional] |
| **min_rating** | **Float** | Filter to hotels with at least this guest rating. | [optional] |
| **sort_by** | **String** | Sort order for results. Defaults to relevance. | [optional] |
| **min_price** | **Integer** | Minimum price per night. | [optional] |
| **max_price** | **Integer** | Maximum price per night. | [optional] |
| **free_cancellation** | **Boolean** | When true, only return hotels offering free cancellation. | [optional] |
| **is_vacation_rentals** | **Boolean** | When true, search vacation rentals instead of hotels. | [optional] |
| **amenities** | **Array&lt;String&gt;** | Filter to hotels offering these amenities, such as pool or free_wifi. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::HotelSearchRequest.new(
  query: null,
  location: null,
  language: null,
  limit: null,
  check_in: null,
  check_out: null,
  currency: null,
  adults: null,
  children: null,
  stars: null,
  min_rating: null,
  sort_by: null,
  min_price: null,
  max_price: null,
  free_cancellation: null,
  is_vacation_rentals: null,
  amenities: null
)
```

