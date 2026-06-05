# Unifapi::SerpListElement

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **rank** | **Integer** | Absolute rank of the element in the result list. | [optional] |
| **group_rank** | **Integer** |  | [optional] |
| **type** | **String** | SERP element type, such as news_search, maps_search, or local_pack. |  |
| **title** | **String** |  | [optional] |
| **url** | **String** |  | [optional] |
| **domain** | **String** |  | [optional] |
| **snippet** | **String** |  | [optional] |
| **image_url** | **String** |  | [optional] |
| **phone** | **String** |  | [optional] |
| **address** | **String** |  | [optional] |
| **rating** | **Object** |  | [optional] |
| **latitude** | **Float** |  | [optional] |
| **longitude** | **Float** |  | [optional] |
| **category** | **String** |  | [optional] |
| **is_paid** | **Boolean** | True when the element is an ad. | [optional] |
| **is_billable** | **Boolean** | True for result elements that count toward billing. Ads are free context. |  |
| **nested_items** | **Array&lt;Object&gt;** |  | [optional] |
| **extras** | **Hash&lt;String, Object&gt;** | Additional element fields preserved in the full view. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SerpListElement.new(
  rank: null,
  group_rank: null,
  type: null,
  title: null,
  url: null,
  domain: null,
  snippet: null,
  image_url: null,
  phone: null,
  address: null,
  rating: null,
  latitude: null,
  longitude: null,
  category: null,
  is_paid: null,
  is_billable: null,
  nested_items: null,
  extras: null
)
```

