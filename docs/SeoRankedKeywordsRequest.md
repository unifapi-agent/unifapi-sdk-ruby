# Unifapi::SeoRankedKeywordsRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Target domain, such as example.com or https://example.com. Specified without www. A page URL can also be passed to get only that page&#39;s rankings. |  |
| **location** | [**SeoRankedKeywordsLocation**](SeoRankedKeywordsLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |
| **limit** | **Integer** | Maximum number of ranked keywords to return. Defaults to 100. | [optional] |
| **offset** | **Integer** | Number of keywords to skip from the start of the results. | [optional] |
| **ignore_synonyms** | **Boolean** | When true, exclude highly similar keyword variations from the results. | [optional] |
| **view** | [**SeoKeywordView**](SeoKeywordView.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoRankedKeywordsRequest.new(
  target: null,
  location: null,
  language: null,
  limit: null,
  offset: null,
  ignore_synonyms: null,
  view: null
)
```

