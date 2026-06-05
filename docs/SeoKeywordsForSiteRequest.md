# Unifapi::SeoKeywordsForSiteRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Target domain, such as example.com or https://example.com. Returns keywords the domain is relevant for. |  |
| **location** | [**SeoKeywordsForSiteLocation**](SeoKeywordsForSiteLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |
| **limit** | **Integer** | Maximum number of keywords to return. Defaults to 100. | [optional] |
| **offset** | **Integer** | Number of keywords to skip from the start of the results. | [optional] |
| **offset_token** | **String** | Pagination token from a previous response. When set, all other params except limit are ignored. | [optional] |
| **include_subdomains** | **Boolean** | When true (default), include keywords from subdomains of the target. | [optional] |
| **include_serp_info** | **Boolean** | When true, include SERP data (result count and SERP feature types) for each keyword. Can add source cost. | [optional] |
| **view** | [**SeoKeywordView**](SeoKeywordView.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoKeywordsForSiteRequest.new(
  target: null,
  location: null,
  language: null,
  limit: null,
  offset: null,
  offset_token: null,
  include_subdomains: null,
  include_serp_info: null,
  view: null
)
```

