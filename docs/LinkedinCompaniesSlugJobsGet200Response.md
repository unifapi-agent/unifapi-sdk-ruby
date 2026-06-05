# Unifapi::LinkedinCompaniesSlugJobsGet200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **request_id** | **String** | UnifAPI request id for support and ledger correlation. |  |
| **data** | [**Array&lt;LinkedinJobListing&gt;**](LinkedinJobListing.md) |  |  |
| **pagination** | [**Pagination**](Pagination.md) |  |  |
| **billing** | [**Billing**](Billing.md) |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::LinkedinCompaniesSlugJobsGet200Response.new(
  request_id: null,
  data: null,
  pagination: null,
  billing: null
)
```

