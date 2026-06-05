# Unifapi::RedditComment

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | Comment id (&#x60;t1_*&#x60; fullname). |  |
| **text** | **String** |  |  |
| **created_at** | **String** |  |  |
| **score** | **Float** |  |  |
| **author_name** | **String** |  |  |
| **is_locked** | **Boolean** |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::RedditComment.new(
  id: null,
  text: null,
  created_at: null,
  score: null,
  author_name: null,
  is_locked: null
)
```

