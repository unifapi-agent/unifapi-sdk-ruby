# Unifapi::SeoBacklinksBulkNewLostReferringDomainsResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **results** | [**Array&lt;SeoBacklinksBulkNewLostReferringDomainsItem&gt;**](SeoBacklinksBulkNewLostReferringDomainsItem.md) | New and lost referring domain counts for each requested target. Each target is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksBulkNewLostReferringDomainsResponse.new(
  results: null
)
```

