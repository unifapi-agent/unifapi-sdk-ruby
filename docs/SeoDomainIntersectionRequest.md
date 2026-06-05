# Unifapi::SeoDomainIntersectionRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target1** | **String** | First domain, such as example.com. |  |
| **target2** | **String** | Second domain to compare against. |  |
| **location** | [**SeoDomainIntersectionLocation**](SeoDomainIntersectionLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |
| **intersections** | **Boolean** | When true (default), return keywords both domains rank for. When false, return keywords the first domain ranks for but the second does not. | [optional] |
| **limit** | **Integer** | Maximum number of keywords to return. Defaults to 100. | [optional] |
| **offset** | **Integer** | Number of keywords to skip from the start of the results. | [optional] |
| **view** | [**SeoKeywordView**](SeoKeywordView.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoDomainIntersectionRequest.new(
  target1: null,
  target2: null,
  location: null,
  language: null,
  intersections: null,
  limit: null,
  offset: null,
  view: null
)
```

