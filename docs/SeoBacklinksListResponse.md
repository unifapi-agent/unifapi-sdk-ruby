# Unifapi::SeoBacklinksListResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Target echoed from the request. |  |
| **view** | [**SeoBacklinksView**](SeoBacklinksView.md) |  |  |
| **mode** | **String** | Result grouping applied to the backlinks. | [optional] |
| **total_count** | **Integer** | Total number of backlinks available in DataForSEO&#39;s database. | [optional] |
| **search_after_token** | **String** | Token to pass as search_after_token to fetch the next page of backlinks. | [optional] |
| **results** | [**Array&lt;SeoBacklinkItem&gt;**](SeoBacklinkItem.md) | Individual backlinks pointing to the target. Each backlink is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksListResponse.new(
  target: null,
  view: null,
  mode: null,
  total_count: null,
  search_after_token: null,
  results: null
)
```

