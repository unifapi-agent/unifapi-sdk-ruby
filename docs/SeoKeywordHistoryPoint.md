# Unifapi::SeoKeywordHistoryPoint

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **year** | **Integer** | Year of the data point. |  |
| **month** | **Integer** | Month of the data point (1-12). | [optional] |
| **search_volume** | **Integer** | Average monthly search volume. | [optional] |
| **cpc** | **Float** | Average cost-per-click in USD. | [optional] |
| **competition** | **Float** | Google Ads competition index between 0 and 1. | [optional] |
| **competition_level** | **String** | Google Ads competition level: LOW, MEDIUM, or HIGH. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoKeywordHistoryPoint.new(
  year: null,
  month: null,
  search_volume: null,
  cpc: null,
  competition: null,
  competition_level: null
)
```

