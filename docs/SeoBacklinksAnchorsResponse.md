# Unifapi::SeoBacklinksAnchorsResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Target echoed from the request. |  |
| **view** | [**SeoBacklinksView**](SeoBacklinksView.md) |  |  |
| **total_count** | **Integer** | Total number of anchor texts available in DataForSEO&#39;s database. | [optional] |
| **results** | [**Array&lt;SeoBacklinksAnchorItem&gt;**](SeoBacklinksAnchorItem.md) | Anchor texts used in backlinks to the target, with backlink counters. Each anchor is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksAnchorsResponse.new(
  target: null,
  view: null,
  total_count: null,
  results: null
)
```

