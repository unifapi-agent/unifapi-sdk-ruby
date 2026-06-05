# Unifapi::SeoBacklinksBulkRanksResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **results** | [**Array&lt;SeoBacklinksBulkRankItem&gt;**](SeoBacklinksBulkRankItem.md) | Backlink rank for each requested target. Each target is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksBulkRanksResponse.new(
  results: null
)
```

