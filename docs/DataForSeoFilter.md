# Unifapi::DataForSeoFilter

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **field** | **String** | Field to filter on. See the endpoint&#39;s list of filterable fields. |  |
| **op** | **String** | Comparison operator. |  |
| **value** | [**DataForSeoFilterValue**](DataForSeoFilterValue.md) |  |  |
| **_and** | [**Array&lt;DataForSeoFilter&gt;**](DataForSeoFilter.md) | Sub-expressions that must all match. |  |
| **_or** | [**Array&lt;DataForSeoFilter&gt;**](DataForSeoFilter.md) | Sub-expressions where at least one must match. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::DataForSeoFilter.new(
  field: null,
  op: null,
  value: null,
  _and: null,
  _or: null
)
```

