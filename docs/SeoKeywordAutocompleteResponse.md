# Unifapi::SeoKeywordAutocompleteResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **keyword** | **String** |  |  |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **observed_at** | **String** |  | [optional] |
| **search_url** | **String** |  | [optional] |
| **result_count** | **Integer** | Number of suggestions returned. |  |
| **results** | [**Array&lt;SeoAutocompleteSuggestion&gt;**](SeoAutocompleteSuggestion.md) | Autocomplete suggestions for SEO keyword discovery. Each suggestion is billable. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoKeywordAutocompleteResponse.new(
  keyword: null,
  location: null,
  language: null,
  observed_at: null,
  search_url: null,
  result_count: null,
  results: null
)
```

