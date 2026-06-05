# Unifapi::SeoPageIntersectionRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **pages** | **Array&lt;String&gt;** | Absolute page URLs to compare (1-20). A trailing /* wildcard matches a page and its sub-paths. |  |
| **exclude_pages** | **Array&lt;String&gt;** | Page URLs to exclude (up to 10). Keywords where these rank are dropped. | [optional] |
| **location** | [**SeoPageIntersectionLocation**](SeoPageIntersectionLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |
| **intersection_mode** | **String** | union (default) returns keywords any page ranks for; intersect returns only keywords all pages rank for in the same SERP. | [optional] |
| **limit** | **Integer** | Maximum number of keywords to return. Defaults to 100. | [optional] |
| **offset** | **Integer** | Number of keywords to skip from the start of the results. | [optional] |
| **view** | [**SeoKeywordView**](SeoKeywordView.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoPageIntersectionRequest.new(
  pages: null,
  exclude_pages: null,
  location: null,
  language: null,
  intersection_mode: null,
  limit: null,
  offset: null,
  view: null
)
```

