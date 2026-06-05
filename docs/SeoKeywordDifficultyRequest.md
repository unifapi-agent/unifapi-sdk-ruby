# Unifapi::SeoKeywordDifficultyRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **keywords** | **Array&lt;String&gt;** | Keywords to score (1-1000). Returns the keyword difficulty for each. |  |
| **location** | [**SeoKeywordDifficultyLocation**](SeoKeywordDifficultyLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoKeywordDifficultyRequest.new(
  keywords: null,
  location: null,
  language: null
)
```

