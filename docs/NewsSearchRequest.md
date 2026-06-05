# Unifapi::NewsSearchRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **query** | **String** | Search query to inspect. |  |
| **location** | [**SerpListLocation**](SerpListLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |
| **limit** | **Integer** | Number of results to return, matching the limit parameter used across other UnifAPI endpoints. Maps to result depth. | [optional] |
| **view** | [**SerpListView**](SerpListView.md) |  | [optional] |
| **os** | [**SerpListOs**](SerpListOs.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::NewsSearchRequest.new(
  query: null,
  location: null,
  language: null,
  limit: null,
  view: null,
  os: null
)
```

