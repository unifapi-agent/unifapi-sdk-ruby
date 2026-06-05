# Unifapi::TiktokMusicIdGet200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **request_id** | **String** | UnifAPI request id for support and ledger correlation. |  |
| **data** | [**MusicDetail**](MusicDetail.md) |  |  |
| **billing** | [**Billing**](Billing.md) |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::TiktokMusicIdGet200Response.new(
  request_id: null,
  data: null,
  billing: null
)
```

