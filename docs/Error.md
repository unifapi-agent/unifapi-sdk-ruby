# Unifapi::Error

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **type** | **String** | Closed vocabulary - see docs/adr/0003-error-model.md. |  |
| **message** | **String** |  |  |
| **request_id** | **String** | UnifAPI request id, e.g. &#x60;unif_&lt;id&gt;&#x60;. Source ids are not exposed. | [optional] |
| **issues** | **Array&lt;Object&gt;** | Present only when type&#x3D;validation_error. | [optional] |
| **billing** | [**ErrorBilling**](ErrorBilling.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::Error.new(
  type: null,
  message: null,
  request_id: null,
  issues: null,
  billing: null
)
```

