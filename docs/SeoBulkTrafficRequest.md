# Unifapi::SeoBulkTrafficRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **targets** | **Array&lt;String&gt;** | Domains to estimate traffic for (1-1000). |  |
| **location** | [**SeoBulkTrafficLocation**](SeoBulkTrafficLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |
| **view** | [**SeoDomainMetricsView**](SeoDomainMetricsView.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBulkTrafficRequest.new(
  targets: null,
  location: null,
  language: null,
  view: null
)
```

