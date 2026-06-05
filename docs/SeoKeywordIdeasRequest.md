# Unifapi::SeoKeywordIdeasRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **keywords** | **Array&lt;String&gt;** | Seed keywords (1-200). Returns search terms relevant to the product or service categories of these keywords. |  |
| **location** | [**SeoKeywordIdeasLocation**](SeoKeywordIdeasLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |
| **limit** | **Integer** | Maximum number of keyword ideas to return. Defaults to 100. | [optional] |
| **offset** | **Integer** | Number of keyword ideas to skip from the start of the results. | [optional] |
| **offset_token** | **String** | Pagination token from a previous response. When set, all other params except limit are ignored. | [optional] |
| **closely_variants** | **Boolean** | When true, use phrase-match search; when false (default), use broad-match search for wider ideas. | [optional] |
| **ignore_synonyms** | **Boolean** | When true, exclude highly similar keywords and return only core keywords. | [optional] |
| **include_serp_info** | **Boolean** | When true, include SERP data (result count and SERP feature types) for each keyword. Can add source cost. | [optional] |
| **view** | [**SeoKeywordView**](SeoKeywordView.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoKeywordIdeasRequest.new(
  keywords: null,
  location: null,
  language: null,
  limit: null,
  offset: null,
  offset_token: null,
  closely_variants: null,
  ignore_synonyms: null,
  include_serp_info: null,
  view: null
)
```

