# Unifapi::SeoKeywordSearchVolumeTrend

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **monthly** | **Float** | Percentage change versus the previous month. | [optional] |
| **quarterly** | **Float** | Percentage change versus the previous quarter. | [optional] |
| **yearly** | **Float** | Percentage change versus the previous year. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoKeywordSearchVolumeTrend.new(
  monthly: null,
  quarterly: null,
  yearly: null
)
```

