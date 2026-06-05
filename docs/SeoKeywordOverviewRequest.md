# Unifapi::SeoKeywordOverviewRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **keywords** | **Array&lt;String&gt;** | Keywords to look up (1-700). Returns current metrics for each keyword. |  |
| **location** | [**SeoKeywordOverviewLocation**](SeoKeywordOverviewLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |
| **include_serp_info** | **Boolean** | When true, include SERP data (result count and SERP feature types) for each keyword. Can add source cost. | [optional] |
| **view** | [**SeoKeywordView**](SeoKeywordView.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoKeywordOverviewRequest.new(
  keywords: null,
  location: null,
  language: null,
  include_serp_info: null,
  view: null
)
```

