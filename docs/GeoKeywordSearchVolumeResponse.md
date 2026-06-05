# Unifapi::GeoKeywordSearchVolumeResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **results** | [**Array&lt;GeoKeywordSearchVolumeRecord&gt;**](GeoKeywordSearchVolumeRecord.md) | One billable record per keyword with AI search volume and monthly trend. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::GeoKeywordSearchVolumeResponse.new(
  location: null,
  language: null,
  results: null
)
```

