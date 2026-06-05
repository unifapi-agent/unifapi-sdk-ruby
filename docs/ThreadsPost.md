# Unifapi::ThreadsPost

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | Threads post code (URL slug). |  |
| **code** | **String** |  |  |
| **media_id** | **String** |  |  |
| **text** | **String** |  |  |
| **taken_at** | **Float** |  |  |
| **like_count** | **Float** |  |  |
| **image_url** | **String** |  |  |
| **video_url** | **String** |  |  |
| **user** | [**ThreadsPostUser**](ThreadsPostUser.md) |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::ThreadsPost.new(
  id: null,
  code: null,
  media_id: null,
  text: null,
  taken_at: null,
  like_count: null,
  image_url: null,
  video_url: null,
  user: null
)
```

