# Unifapi::GeoSerpPost200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **request_id** | **String** | UnifAPI request id for support and ledger correlation. |  |
| **data** | [**GeoSerpResponse**](GeoSerpResponse.md) |  |  |
| **billing** | [**Billing**](Billing.md) |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::GeoSerpPost200Response.new(
  request_id: null,
  data: null,
  billing: null
)
```

