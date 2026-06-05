# Unifapi::GeoSerpSection

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **type** | **String** |  |  |
| **title** | **String** |  | [optional] |
| **text** | **String** |  | [optional] |
| **markdown** | **String** |  | [optional] |
| **url** | **String** |  | [optional] |
| **domain** | **String** |  | [optional] |
| **source** | **String** |  | [optional] |
| **snippet** | **String** |  | [optional] |
| **references** | [**Array&lt;GeoSerpReference&gt;**](GeoSerpReference.md) |  | [optional] |
| **links** | [**Array&lt;GeoSerpLink&gt;**](GeoSerpLink.md) |  | [optional] |
| **images** | [**Array&lt;GeoSerpImage&gt;**](GeoSerpImage.md) |  | [optional] |
| **table** | **Object** |  | [optional] |
| **nested_items** | **Array&lt;Object&gt;** |  | [optional] |
| **is_target** | **Boolean** |  | [optional] |
| **extras** | **Hash&lt;String, Object&gt;** |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::GeoSerpSection.new(
  type: null,
  title: null,
  text: null,
  markdown: null,
  url: null,
  domain: null,
  source: null,
  snippet: null,
  references: null,
  links: null,
  images: null,
  table: null,
  nested_items: null,
  is_target: null,
  extras: null
)
```

