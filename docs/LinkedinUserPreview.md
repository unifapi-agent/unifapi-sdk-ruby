# Unifapi::LinkedinUserPreview

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **urn** | **String** |  |  |
| **username** | **String** |  |  |
| **display_name** | **String** |  |  |
| **headline** | **String** |  |  |
| **location** | **String** |  |  |
| **avatar_url** | **String** |  |  |
| **url** | **String** |  |  |
| **is_verified** | **Boolean** |  |  |
| **is_premium** | **Boolean** |  |  |
| **is_top_voice** | **Boolean** |  |  |
| **is_open_to_work** | **Boolean** |  |  |
| **is_hiring** | **Boolean** |  |  |
| **follower_count** | **Integer** | Present in company employee listings, null in plain search results. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::LinkedinUserPreview.new(
  id: null,
  urn: null,
  username: null,
  display_name: null,
  headline: null,
  location: null,
  avatar_url: null,
  url: null,
  is_verified: null,
  is_premium: null,
  is_top_voice: null,
  is_open_to_work: null,
  is_hiring: null,
  follower_count: null
)
```

