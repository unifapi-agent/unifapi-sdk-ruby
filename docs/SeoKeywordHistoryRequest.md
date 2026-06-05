# Unifapi::SeoKeywordHistoryRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **keywords** | **Array&lt;String&gt;** | Keywords to look up (1-700). Returns historical metrics since 2019 for each. |  |
| **location** | [**SeoKeywordHistoryLocation**](SeoKeywordHistoryLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoKeywordHistoryRequest.new(
  keywords: null,
  location: null,
  language: null
)
```

