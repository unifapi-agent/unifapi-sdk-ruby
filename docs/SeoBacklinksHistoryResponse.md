# Unifapi::SeoBacklinksHistoryResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Target echoed from the request. |  |
| **view** | [**SeoBacklinksView**](SeoBacklinksView.md) |  |  |
| **date_from** | **String** | Start date of the history echoed from the request. | [optional] |
| **date_to** | **String** | End date of the history echoed from the request. | [optional] |
| **series** | [**Array&lt;SeoBacklinksHistoryItem&gt;**](SeoBacklinksHistoryItem.md) | Monthly snapshots of the target&#39;s backlink profile, oldest to newest. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksHistoryResponse.new(
  target: null,
  view: null,
  date_from: null,
  date_to: null,
  series: null
)
```

