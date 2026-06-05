# Unifapi::SeoReferringDomainsResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Target echoed from the request. |  |
| **view** | [**SeoBacklinksView**](SeoBacklinksView.md) |  |  |
| **total_count** | **Integer** | Total number of referring domains available in DataForSEO&#39;s database. | [optional] |
| **results** | [**Array&lt;SeoReferringDomainItem&gt;**](SeoReferringDomainItem.md) | Referring domains pointing to the target, with backlink counters. Each domain is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoReferringDomainsResponse.new(
  target: null,
  view: null,
  total_count: null,
  results: null
)
```

