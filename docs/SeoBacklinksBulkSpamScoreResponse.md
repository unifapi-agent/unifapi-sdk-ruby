# Unifapi::SeoBacklinksBulkSpamScoreResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **results** | [**Array&lt;SeoBacklinksBulkSpamScoreItem&gt;**](SeoBacklinksBulkSpamScoreItem.md) | Spam score for each requested target. Each target is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksBulkSpamScoreResponse.new(
  results: null
)
```

