# Unifapi::SeoAutocompleteSuggestion

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **rank** | **Integer** | Absolute rank of the suggestion in the list. | [optional] |
| **suggestion** | **String** | Google autocomplete keyword suggestion. |  |
| **relevance** | **Integer** | Relevance score Google assigns to the suggestion. | [optional] |
| **suggestion_type** | **String** | Category Google assigns to the suggestion, such as Search or Navigation. | [optional] |
| **search_query_url** | **String** | Google search URL the suggestion resolves to. | [optional] |
| **thumbnail_url** | **String** | Thumbnail image URL when Google attaches one to the suggestion. | [optional] |
| **highlighted** | **Array&lt;String&gt;** | Substrings highlighted by Google within the suggestion. | [optional] |
| **is_billable** | **Boolean** | Each suggestion is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoAutocompleteSuggestion.new(
  rank: null,
  suggestion: null,
  relevance: null,
  suggestion_type: null,
  search_query_url: null,
  thumbnail_url: null,
  highlighted: null,
  is_billable: null
)
```

