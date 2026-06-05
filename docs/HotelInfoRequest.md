# Unifapi::HotelInfoRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **hotel_identifier** | **String** | Unique hotel id returned by /hotels/search. |  |
| **location** | [**HotelInfoLocation**](HotelInfoLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |
| **check_in** | **String** | Check-in date. Date in YYYY-MM-DD format. | [optional] |
| **check_out** | **String** | Check-out date. Date in YYYY-MM-DD format. | [optional] |
| **currency** | **String** | ISO 4217 currency code for prices, such as USD. | [optional] |
| **adults** | **Integer** | Number of adult guests. | [optional] |
| **children** | **Array&lt;Integer&gt;** | Ages of children staying, used to refine availability and pricing. | [optional] |
| **load_prices_by_dates** | **Boolean** | When true, return a daily price calendar across the requested date range instead of a single stay price. | [optional] |
| **prices_start_date** | **String** | Start date for the daily price calendar. Date in YYYY-MM-DD format. | [optional] |
| **prices_end_date** | **String** | End date for the daily price calendar. Date in YYYY-MM-DD format. | [optional] |
| **prices_date_range** | **String** | Predefined period for the daily price calendar, such as next_30_days. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::HotelInfoRequest.new(
  hotel_identifier: null,
  location: null,
  language: null,
  check_in: null,
  check_out: null,
  currency: null,
  adults: null,
  children: null,
  load_prices_by_dates: null,
  prices_start_date: null,
  prices_end_date: null,
  prices_date_range: null
)
```

