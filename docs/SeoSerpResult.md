# Unifapi::SeoSerpResult

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **rank** | **Integer** |  | [optional] |
| **source_rank** | **Integer** | Rank reported by DataForSEO before page offset adjustment. | [optional] |
| **group_rank** | **Integer** |  | [optional] |
| **type** | **String** |  |  |
| **title** | **String** |  | [optional] |
| **url** | **String** |  | [optional] |
| **domain** | **String** |  | [optional] |
| **snippet** | **String** |  | [optional] |
| **text** | **String** |  | [optional] |
| **markdown** | **String** |  | [optional] |
| **breadcrumb** | **String** |  | [optional] |
| **page** | **Integer** |  | [optional] |
| **position** | **Object** |  | [optional] |
| **rectangle** | **Object** |  | [optional] |
| **is_paid** | **Boolean** |  | [optional] |
| **is_billable** | **Boolean** | True for organic search result records that count toward billing. |  |
| **is_target** | **Boolean** |  | [optional] |
| **questions** | **Array&lt;String&gt;** | People Also Ask questions extracted from this SERP element. | [optional] |
| **nested_items** | **Array&lt;Object&gt;** |  | [optional] |
| **extras** | **Hash&lt;String, Object&gt;** | Additional fields for rich SERP elements. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoSerpResult.new(
  rank: null,
  source_rank: null,
  group_rank: null,
  type: null,
  title: null,
  url: null,
  domain: null,
  snippet: null,
  text: null,
  markdown: null,
  breadcrumb: null,
  page: null,
  position: null,
  rectangle: null,
  is_paid: null,
  is_billable: null,
  is_target: null,
  questions: null,
  nested_items: null,
  extras: null
)
```

