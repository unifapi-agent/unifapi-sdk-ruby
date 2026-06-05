# Unifapi::HotelSearchResultPrices

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **price** | **Float** | Nightly price in the response currency. | [optional] |
| **price_without_discount** | **Float** | Full nightly price before any discount, when a discount applies. | [optional] |
| **currency** | **String** | ISO 4217 currency code for the price, such as USD. | [optional] |
| **discount_text** | **String** | Discount label, such as \&quot;23% less than usual\&quot;. | [optional] |
| **prices_by_dates** | [**Array&lt;HotelPriceByDate&gt;**](HotelPriceByDate.md) | Daily price calendar, populated when /hotels/info requests load_prices_by_dates. | [optional] |
| **extras** | **Hash** |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::HotelSearchResultPrices.new(
  price: null,
  price_without_discount: null,
  currency: null,
  discount_text: null,
  prices_by_dates: null,
  extras: null
)
```

