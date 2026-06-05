# Unifapi::SeoKeywordSuggestionsRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **keyword** | **String** | Seed keyword. Returns long-tail search queries that include this keyword. |  |
| **location** | [**SeoKeywordSuggestionsLocation**](SeoKeywordSuggestionsLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |
| **limit** | **Integer** | Maximum number of keyword suggestions to return. Defaults to 100. | [optional] |
| **offset** | **Integer** | Number of keyword suggestions to skip from the start of the results. | [optional] |
| **offset_token** | **String** | Pagination token from a previous response. When set, all other params except limit are ignored. | [optional] |
| **exact_match** | **Boolean** | When true, return only suggestions that contain the exact seed keyword in the same word order. | [optional] |
| **ignore_synonyms** | **Boolean** | When true, exclude highly similar keywords and return only core keywords. | [optional] |
| **include_serp_info** | **Boolean** | When true, include SERP data (result count and SERP feature types) for each keyword. Can add source cost. | [optional] |
| **include_seed_keyword** | **Boolean** | When true, include metrics for the seed keyword in the response. | [optional] |
| **view** | [**SeoKeywordView**](SeoKeywordView.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoKeywordSuggestionsRequest.new(
  keyword: null,
  location: null,
  language: null,
  limit: null,
  offset: null,
  offset_token: null,
  exact_match: null,
  ignore_synonyms: null,
  include_serp_info: null,
  include_seed_keyword: null,
  view: null
)
```

