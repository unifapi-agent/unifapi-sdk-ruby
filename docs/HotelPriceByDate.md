# Unifapi::HotelPriceByDate

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **price** | **Float** | Nightly price for this date in the response currency. | [optional] |
| **currency** | **String** | ISO 4217 currency code for the price. | [optional] |
| **check_in_date** | **String** | Check-in date for this calendar entry. | [optional] |
| **check_out_date** | **String** | Check-out date for this calendar entry. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::HotelPriceByDate.new(
  price: null,
  currency: null,
  check_in_date: null,
  check_out_date: null
)
```

