# Unifapi::LinkedinUsersUsernameInterestsGroupsGet200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **request_id** | **String** | UnifAPI request id for support and ledger correlation. |  |
| **data** | [**Array&lt;LinkedinInterestGroup&gt;**](LinkedinInterestGroup.md) |  |  |
| **pagination** | [**Pagination**](Pagination.md) |  |  |
| **billing** | [**Billing**](Billing.md) |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::LinkedinUsersUsernameInterestsGroupsGet200Response.new(
  request_id: null,
  data: null,
  pagination: null,
  billing: null
)
```

