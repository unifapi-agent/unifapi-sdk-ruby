# Unifapi::HotelAbout

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **description** | **String** | Hotel description. | [optional] |
| **full_address** | **String** | Standardised full address of the hotel. | [optional] |
| **domain** | **String** | Domain of the hotel&#39;s website. | [optional] |
| **url** | **String** | URL of the hotel&#39;s website. | [optional] |
| **check_in_time** | **String** | Listed check-in time as HH:MM (24-hour). | [optional] |
| **check_out_time** | **String** | Listed check-out time as HH:MM (24-hour). | [optional] |
| **amenities** | **Array&lt;String&gt;** | Available amenity labels offered by the hotel. | [optional] |
| **extras** | **Hash&lt;String, Object&gt;** | Additional descriptive detail such as sub-descriptions and amenity categories. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::HotelAbout.new(
  description: null,
  full_address: null,
  domain: null,
  url: null,
  check_in_time: null,
  check_out_time: null,
  amenities: null,
  extras: null
)
```

