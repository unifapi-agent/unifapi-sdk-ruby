# Unifapi::SeoKeywordMonthlySearch

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **year** | **Integer** | Calendar year of the data point. |  |
| **month** | **Integer** | Month number, 1-12. |  |
| **search_volume** | **Integer** | Average Google search volume for that month. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoKeywordMonthlySearch.new(
  year: null,
  month: null,
  search_volume: null
)
```

