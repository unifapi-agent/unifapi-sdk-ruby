# Unifapi::SeoKeywordHistoryItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **keyword** | **String** | Keyword phrase. |  |
| **history** | [**Array&lt;SeoKeywordHistoryPoint&gt;**](SeoKeywordHistoryPoint.md) | Historical search-volume and Google Ads metrics, newest first. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoKeywordHistoryItem.new(
  keyword: null,
  history: null
)
```

