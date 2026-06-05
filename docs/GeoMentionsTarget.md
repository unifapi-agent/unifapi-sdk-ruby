# Unifapi::GeoMentionsTarget

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **domain** | **String** | Target domain (no protocol/www). Provide domain or keyword. | [optional] |
| **keyword** | **String** | Target keyword. Provide domain or keyword. | [optional] |
| **filter** | **String** | Whether to include or exclude matches for this entity. Defaults to include. | [optional] |
| **scope** | **Array&lt;String&gt;** | Where to look. Domain scopes: any, sources, search_results. Keyword scopes: any, question, answer, brand_entities, fan_out_queries. | [optional] |
| **match** | **String** | Keyword match type. word &#x3D; full-term match; partial &#x3D; substring. Defaults to word. | [optional] |
| **include_subdomains** | **Boolean** | Include subdomains of the target domain. Defaults to false. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::GeoMentionsTarget.new(
  domain: null,
  keyword: null,
  filter: null,
  scope: null,
  match: null,
  include_subdomains: null
)
```

