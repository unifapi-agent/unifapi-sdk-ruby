# Unifapi::SeoBacklinksBulkNewLostBacklinksResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **results** | [**Array&lt;SeoBacklinksBulkNewLostBacklinksItem&gt;**](SeoBacklinksBulkNewLostBacklinksItem.md) | New and lost backlink counts for each requested target. Each target is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksBulkNewLostBacklinksResponse.new(
  results: null
)
```

