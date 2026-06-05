# Unifapi::User

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | Stable TikTok user id. |  |
| **username** | **String** |  |  |
| **display_name** | **String** |  |  |
| **avatar_url** | **String** |  |  |
| **bio** | **String** |  |  |
| **is_verified** | **Boolean** |  |  |
| **is_private** | **Boolean** |  |  |
| **follower_count** | **Integer** |  |  |
| **following_count** | **Integer** |  |  |
| **like_count** | **Integer** | Total likes received across posts |  |
| **video_count** | **Integer** |  |  |
| **region** | **String** |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::User.new(
  id: null,
  username: null,
  display_name: null,
  avatar_url: null,
  bio: null,
  is_verified: null,
  is_private: null,
  follower_count: null,
  following_count: null,
  like_count: null,
  video_count: null,
  region: null
)
```

