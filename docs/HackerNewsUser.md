# Unifapi::HackerNewsUser

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **created** | **Integer** | Unix epoch seconds | [optional] |
| **karma** | **Integer** |  | [optional] |
| **about** | **String** | HTML profile text. | [optional] |
| **submitted** | **Array&lt;Integer&gt;** |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::HackerNewsUser.new(
  id: null,
  created: null,
  karma: null,
  about: null,
  submitted: null
)
```

