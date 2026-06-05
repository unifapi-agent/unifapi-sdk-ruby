# Unifapi::ThreadsUser

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | Threads URL slug (&#x60;username&#x60;). |  |
| **user_id** | **String** | Numeric Threads pk; surfaced for callers that want to skip the gateway-side username → pk stitch. |  |
| **username** | **String** |  |  |
| **full_name** | **String** |  |  |
| **biography** | **String** |  |  |
| **profile_pic_url** | **String** |  |  |
| **follower_count** | **Float** |  |  |
| **is_verified** | **Boolean** |  |  |
| **is_private** | **Boolean** |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::ThreadsUser.new(
  id: null,
  user_id: null,
  username: null,
  full_name: null,
  biography: null,
  profile_pic_url: null,
  follower_count: null,
  is_verified: null,
  is_private: null
)
```

