# Unifapi::SeoRelevantPagesRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Target domain, such as example.com or https://example.com. Specified without www. |  |
| **location** | [**SeoRelevantPagesLocation**](SeoRelevantPagesLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |
| **limit** | **Integer** | Maximum number of pages to return. Defaults to 100. | [optional] |
| **offset** | **Integer** | Number of pages to skip from the start of the results. | [optional] |
| **view** | [**SeoDomainMetricsView**](SeoDomainMetricsView.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoRelevantPagesRequest.new(
  target: null,
  location: null,
  language: null,
  limit: null,
  offset: null,
  view: null
)
```

