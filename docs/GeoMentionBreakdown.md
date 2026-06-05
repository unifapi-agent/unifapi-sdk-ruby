# Unifapi::GeoMentionBreakdown

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **by_platform** | [**Array&lt;GeoGroupMetric&gt;**](GeoGroupMetric.md) |  | [optional] |
| **by_location** | [**Array&lt;GeoGroupMetric&gt;**](GeoGroupMetric.md) |  | [optional] |
| **by_language** | [**Array&lt;GeoGroupMetric&gt;**](GeoGroupMetric.md) |  | [optional] |
| **by_source_domain** | [**Array&lt;GeoGroupMetric&gt;**](GeoGroupMetric.md) |  | [optional] |
| **by_search_results_domain** | [**Array&lt;GeoGroupMetric&gt;**](GeoGroupMetric.md) |  | [optional] |
| **by_brand_entity_title** | [**Array&lt;GeoGroupMetric&gt;**](GeoGroupMetric.md) |  | [optional] |
| **by_brand_entity_category** | [**Array&lt;GeoGroupMetric&gt;**](GeoGroupMetric.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::GeoMentionBreakdown.new(
  by_platform: null,
  by_location: null,
  by_language: null,
  by_source_domain: null,
  by_search_results_domain: null,
  by_brand_entity_title: null,
  by_brand_entity_category: null
)
```

