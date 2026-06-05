# Unifapi::DataForSeoFilterCondition

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **field** | **String** | Field to filter on. See the endpoint&#39;s list of filterable fields. |  |
| **op** | **String** | Comparison operator. |  |
| **value** | [**DataForSeoFilterValue**](DataForSeoFilterValue.md) |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::DataForSeoFilterCondition.new(
  field: null,
  op: null,
  value: null
)
```

