# Unifapi::GeoSerpResult

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **rank** | **Integer** |  | [optional] |
| **group_rank** | **Integer** |  | [optional] |
| **type** | **String** |  |  |
| **title** | **String** |  | [optional] |
| **text** | **String** |  | [optional] |
| **markdown** | **String** |  | [optional] |
| **page** | **Integer** |  | [optional] |
| **position** | **String** |  | [optional] |
| **references** | [**Array&lt;GeoSerpReference&gt;**](GeoSerpReference.md) |  | [optional] |
| **links** | [**Array&lt;GeoSerpLink&gt;**](GeoSerpLink.md) |  | [optional] |
| **images** | [**Array&lt;GeoSerpImage&gt;**](GeoSerpImage.md) |  | [optional] |
| **sections** | [**Array&lt;GeoSerpSection&gt;**](GeoSerpSection.md) |  | [optional] |
| **is_billable** | **Boolean** | True for top-level AI SERP result records that count toward billing. |  |
| **is_target** | **Boolean** |  | [optional] |
| **extras** | **Hash&lt;String, Object&gt;** |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::GeoSerpResult.new(
  rank: null,
  group_rank: null,
  type: null,
  title: null,
  text: null,
  markdown: null,
  page: null,
  position: null,
  references: null,
  links: null,
  images: null,
  sections: null,
  is_billable: null,
  is_target: null,
  extras: null
)
```

