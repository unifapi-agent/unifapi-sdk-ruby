# Unifapi::SeoBacklinksTimeseriesNewLostItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **date** | **String** | Last day of the grouped period. |  |
| **new_backlinks** | **Integer** | Backlinks gained during the period. | [optional] |
| **lost_backlinks** | **Integer** | Backlinks lost during the period. | [optional] |
| **new_referring_domains** | **Integer** | Referring domains gained during the period. | [optional] |
| **lost_referring_domains** | **Integer** | Referring domains lost during the period. | [optional] |
| **new_referring_main_domains** | **Integer** | Referring root domains gained during the period. | [optional] |
| **lost_referring_main_domains** | **Integer** | Referring root domains lost during the period. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksTimeseriesNewLostItem.new(
  date: null,
  new_backlinks: null,
  lost_backlinks: null,
  new_referring_domains: null,
  lost_referring_domains: null,
  new_referring_main_domains: null,
  lost_referring_main_domains: null
)
```

