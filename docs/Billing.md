# Unifapi::Billing

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **credits_charged** | **Integer** |  |  |
| **records_charged** | **Integer** |  |  |
| **balance_remaining** | **Integer** |  |  |
| **truncated_due_to_balance** | **Boolean** |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::Billing.new(
  credits_charged: null,
  records_charged: null,
  balance_remaining: null,
  truncated_due_to_balance: null
)
```

