# Unifapi::LinkedinUser

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | LinkedIn URL slug (public_identifier). Use this as the path parameter for every /linkedin/users/{id}/... endpoint. |  |
| **urn** | **String** | LinkedIn internal URN (e.g. &#x60;ACoAA...&#x60;). Stable across username changes; required by certain LinkedIn-internal flows. |  |
| **username** | **String** | Same value as &#x60;id&#x60;; included for cross-platform field parity. |  |
| **display_name** | **String** |  |  |
| **first_name** | **String** |  |  |
| **last_name** | **String** |  |  |
| **headline** | **String** |  |  |
| **avatar_url** | **String** |  |  |
| **cover_image_url** | **String** |  |  |
| **location** | [**LinkedinLocation**](LinkedinLocation.md) |  |  |
| **is_premium** | **Boolean** |  |  |
| **is_open_to_work** | **Boolean** |  |  |
| **is_hiring** | **Boolean** |  |  |
| **is_creator** | **Boolean** |  |  |
| **is_influencer** | **Boolean** |  |  |
| **is_top_voice** | **Boolean** |  |  |
| **is_memorialized** | **Boolean** |  |  |
| **created_at** | **String** |  |  |
| **website_url** | **String** |  |  |
| **associated_hashtags** | **Array&lt;String&gt;** |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::LinkedinUser.new(
  id: null,
  urn: null,
  username: null,
  display_name: null,
  first_name: null,
  last_name: null,
  headline: null,
  avatar_url: null,
  cover_image_url: null,
  location: null,
  is_premium: null,
  is_open_to_work: null,
  is_hiring: null,
  is_creator: null,
  is_influencer: null,
  is_top_voice: null,
  is_memorialized: null,
  created_at: null,
  website_url: null,
  associated_hashtags: null
)
```

