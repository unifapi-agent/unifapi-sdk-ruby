# Unifapi::InstagramComment

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **user** | [**InstagramUserPreview**](InstagramUserPreview.md) |  |  |
| **text** | **String** |  |  |
| **created_at** | **Float** |  |  |
| **like_count** | **Float** |  |  |
| **child_comment_count** | **Float** |  |  |
| **has_translation** | **Boolean** |  |  |
| **has_liked** | **Boolean** |  |  |
| **parent_comment_id** | **String** |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::InstagramComment.new(
  id: null,
  user: null,
  text: null,
  created_at: null,
  like_count: null,
  child_comment_count: null,
  has_translation: null,
  has_liked: null,
  parent_comment_id: null
)
```

