# Unifapi::DataForSeoOrderByRule

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **field** | **String** | Field to sort by. See the endpoint&#39;s list of sortable fields. |  |
| **dir** | **String** | Sort direction: asc or desc. Defaults to desc. | [optional][default to &#39;desc&#39;] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::DataForSeoOrderByRule.new(
  field: null,
  dir: null
)
```

