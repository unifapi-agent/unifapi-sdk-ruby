# Unifapi::Comment

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **video_id** | **String** |  |  |
| **text** | **String** |  |  |
| **create_time** | **Integer** |  |  |
| **like_count** | **Integer** |  |  |
| **reply_count** | **Integer** |  |  |
| **is_author_liked** | **Boolean** |  |  |
| **author** | [**Author**](Author.md) |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::Comment.new(
  id: null,
  video_id: null,
  text: null,
  create_time: null,
  like_count: null,
  reply_count: null,
  is_author_liked: null,
  author: null
)
```

