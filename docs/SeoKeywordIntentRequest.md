# Unifapi::SeoKeywordIntentRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **keywords** | **Array&lt;String&gt;** | Keywords to classify (1-1000). Returns the search intent for each. |  |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoKeywordIntentRequest.new(
  keywords: null,
  language: null
)
```

