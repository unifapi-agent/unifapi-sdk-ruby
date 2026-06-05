# Unifapi::NewsSearchResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **query** | **String** |  |  |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **view** | [**SerpListView**](SerpListView.md) |  |  |
| **observed_at** | **String** |  | [optional] |
| **search_url** | **String** |  | [optional] |
| **item_types** | **Array&lt;String&gt;** | SERP element types present in the result, in source order. |  |
| **total_results** | **Integer** |  | [optional] |
| **result_count** | **Integer** | Number of result elements returned. |  |
| **results** | [**Array&lt;SerpListElement&gt;**](SerpListElement.md) | News SERP elements in source order. News articles and top-stories blocks are billable; ads are free context. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::NewsSearchResponse.new(
  query: null,
  location: null,
  language: null,
  view: null,
  observed_at: null,
  search_url: null,
  item_types: null,
  total_results: null,
  result_count: null,
  results: null
)
```

