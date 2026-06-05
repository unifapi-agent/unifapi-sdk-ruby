# Unifapi::ErrorBilling

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **credits_required** | **Integer** |  | [optional] |
| **credits_charged** | **Integer** |  | [optional] |
| **records_charged** | **Integer** |  | [optional] |
| **balance_remaining** | **Integer** |  |  |
| **truncated_due_to_balance** | **Boolean** |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::ErrorBilling.new(
  credits_required: null,
  credits_charged: null,
  records_charged: null,
  balance_remaining: null,
  truncated_due_to_balance: null
)
```

