# Unifapi::SeoKeywordAutocompleteRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **keyword** | **String** | Seed query typed into Google search. Returns the autocomplete suggestions Google offers. |  |
| **location** | [**SeoAutocompleteLocation**](SeoAutocompleteLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |
| **cursor_pointer** | **Integer** | Cursor position within the keyword. Defaults to the end of the keyword, matching how Google expands suggestions as you type. | [optional] |
| **client** | **String** | Autocomplete client to emulate, such as chrome or gws-wiz. Different clients can return different suggestion sets. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoKeywordAutocompleteRequest.new(
  keyword: null,
  location: null,
  language: null,
  cursor_pointer: null,
  client: null
)
```

