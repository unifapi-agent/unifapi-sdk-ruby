# Unifapi::SeoBacklinksReferringNetworksResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Target echoed from the request. |  |
| **view** | [**SeoBacklinksView**](SeoBacklinksView.md) |  |  |
| **total_count** | **Integer** | Total number of referring networks available in DataForSEO&#39;s database. | [optional] |
| **results** | [**Array&lt;SeoBacklinksReferringNetworkItem&gt;**](SeoBacklinksReferringNetworkItem.md) | Referring IP networks pointing to the target, with backlink counters. Each network is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksReferringNetworksResponse.new(
  target: null,
  view: null,
  total_count: null,
  results: null
)
```

