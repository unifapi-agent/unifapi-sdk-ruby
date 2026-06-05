# Unifapi::TwitterAutocompleteResult

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **query** | **String** |  |  |
| **users** | [**Array&lt;XUser&gt;**](XUser.md) |  |  |
| **topics** | [**Array&lt;TwitterAutocompleteResultTopicsInner&gt;**](TwitterAutocompleteResultTopicsInner.md) |  |  |
| **hashtags** | **Array&lt;String&gt;** |  |  |
| **cashtags** | **Array&lt;String&gt;** |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::TwitterAutocompleteResult.new(
  query: null,
  users: null,
  topics: null,
  hashtags: null,
  cashtags: null
)
```

