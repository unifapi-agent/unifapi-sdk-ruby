# Unifapi::SeoBacklinksBulkNewLostBacklinksRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **targets** | **Array&lt;String&gt;** | Domains, subdomains, or pages to analyze (up to 1000). Domains/subdomains without https:// and www.; pages as absolute URLs. |  |
| **date_from** | **String** | Start date (yyyy-mm-dd) for counting new and lost backlinks. Minimum 2019-01-30; defaults to one month ago. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksBulkNewLostBacklinksRequest.new(
  targets: null,
  date_from: null
)
```

