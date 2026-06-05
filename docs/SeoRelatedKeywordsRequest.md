# Unifapi::SeoRelatedKeywordsRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **keyword** | **String** | Seed keyword. Returns keywords from Google&#39;s &#39;searches related to&#39; element. |  |
| **location** | [**SeoRelatedKeywordsLocation**](SeoRelatedKeywordsLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |
| **depth** | **Integer** | Keyword search depth, 0-4. Higher depth returns more keywords (1≈8, 2≈72, 3≈584, 4≈4680). Defaults to 1. | [optional] |
| **limit** | **Integer** | Maximum number of related keywords to return. Defaults to 100. | [optional] |
| **offset** | **Integer** | Number of related keywords to skip from the start of the results. | [optional] |
| **ignore_synonyms** | **Boolean** | When true, exclude highly similar keywords and return only core keywords. | [optional] |
| **include_serp_info** | **Boolean** | When true, include SERP data (result count and SERP feature types) for each keyword. Can add source cost. | [optional] |
| **include_seed_keyword** | **Boolean** | When true, include metrics for the seed keyword in the response. | [optional] |
| **view** | [**SeoKeywordView**](SeoKeywordView.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoRelatedKeywordsRequest.new(
  keyword: null,
  location: null,
  language: null,
  depth: null,
  limit: null,
  offset: null,
  ignore_synonyms: null,
  include_serp_info: null,
  include_seed_keyword: null,
  view: null
)
```

