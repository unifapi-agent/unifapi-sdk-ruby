# Unifapi::HotelSearchResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **query** | **String** |  | [optional] |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **observed_at** | **String** |  | [optional] |
| **search_url** | **String** |  | [optional] |
| **result_count** | **Integer** | Number of hotels returned. |  |
| **results** | [**Array&lt;HotelSearchResult&gt;**](HotelSearchResult.md) | Hotel listings. Each hotel is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::HotelSearchResponse.new(
  query: null,
  location: null,
  language: null,
  observed_at: null,
  search_url: null,
  result_count: null,
  results: null
)
```

