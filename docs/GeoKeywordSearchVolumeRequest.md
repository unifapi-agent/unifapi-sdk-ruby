# Unifapi::GeoKeywordSearchVolumeRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **keywords** | **Array&lt;String&gt;** | Keywords to look up AI search volume for. Up to 1000 keywords, 250 chars each. |  |
| **location** | [**GeoKeywordSearchVolumeRequestLocation**](GeoKeywordSearchVolumeRequestLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::GeoKeywordSearchVolumeRequest.new(
  keywords: null,
  location: null,
  language: null
)
```

