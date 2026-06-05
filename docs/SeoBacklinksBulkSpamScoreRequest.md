# Unifapi::SeoBacklinksBulkSpamScoreRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **targets** | **Array&lt;String&gt;** | Domains, subdomains, or pages to analyze (up to 1000). Domains/subdomains without https:// and www.; pages as absolute URLs. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksBulkSpamScoreRequest.new(
  targets: null
)
```

