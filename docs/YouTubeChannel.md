# Unifapi::YouTubeChannel

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | YouTube channel id (&#x60;UCxxx&#x60;). |  |
| **title** | **String** |  |  |
| **description** | **String** |  |  |
| **avatar_url** | **String** |  |  |
| **banner_url** | **String** |  |  |
| **subscriber_count** | **Float** |  |  |
| **video_count** | **Float** |  |  |
| **view_count** | **Float** |  |  |
| **country** | **String** |  |  |
| **is_verified** | **Boolean** |  |  |
| **created_at** | **String** | Source creation date string (passed through). |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::YouTubeChannel.new(
  id: null,
  title: null,
  description: null,
  avatar_url: null,
  banner_url: null,
  subscriber_count: null,
  video_count: null,
  view_count: null,
  country: null,
  is_verified: null,
  created_at: null
)
```

