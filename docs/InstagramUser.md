# Unifapi::InstagramUser

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | Instagram URL slug (&#x60;username&#x60;). Path parameter for every /instagram/users/{id}/... endpoint. |  |
| **user_id** | **String** |  |  |
| **username** | **String** |  |  |
| **full_name** | **String** |  |  |
| **is_verified** | **Boolean** |  |  |
| **is_private** | **Boolean** |  |  |
| **profile_pic_url** | **String** |  |  |
| **follower_count** | **Float** |  |  |
| **following_count** | **Float** |  |  |
| **media_count** | **Float** |  |  |
| **fbid_v2** | **String** | Cross-platform Facebook id, when present. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::InstagramUser.new(
  id: null,
  user_id: null,
  username: null,
  full_name: null,
  is_verified: null,
  is_private: null,
  profile_pic_url: null,
  follower_count: null,
  following_count: null,
  media_count: null,
  fbid_v2: null
)
```

