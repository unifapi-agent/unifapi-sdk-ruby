# Unifapi::TiktokSearchHashtagsGet200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **request_id** | **String** | UnifAPI request id for support and ledger correlation. |  |
| **data** | [**Array&lt;Hashtag&gt;**](Hashtag.md) |  |  |
| **pagination** | [**Pagination**](Pagination.md) |  |  |
| **billing** | [**Billing**](Billing.md) |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::TiktokSearchHashtagsGet200Response.new(
  request_id: null,
  data: null,
  pagination: null,
  billing: null
)
```

