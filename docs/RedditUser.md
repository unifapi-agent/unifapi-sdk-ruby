# Unifapi::RedditUser

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | Reddit username (URL slug). |  |
| **user_t2_id** | **String** | Reddit internal user id (&#x60;t2_*&#x60; fullname). |  |
| **name** | **String** |  |  |
| **prefixed_name** | **String** | Display form like &#x60;u/spez&#x60;. |  |
| **karma_total** | **Float** |  |  |
| **karma_from_posts** | **Float** |  |  |
| **karma_from_comments** | **Float** |  |  |
| **is_verified** | **Boolean** |  |  |
| **is_employee** | **Boolean** |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::RedditUser.new(
  id: null,
  user_t2_id: null,
  name: null,
  prefixed_name: null,
  karma_total: null,
  karma_from_posts: null,
  karma_from_comments: null,
  is_verified: null,
  is_employee: null
)
```

