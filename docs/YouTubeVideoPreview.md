# Unifapi::YouTubeVideoPreview

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | YouTube video id (e.g. &#x60;oaSNBz4qMQY&#x60;). |  |
| **title** | **String** |  |  |
| **author** | **String** |  |  |
| **channel_id** | **String** |  |  |
| **description** | **String** |  |  |
| **duration_seconds** | **Float** |  |  |
| **view_count** | **Float** |  |  |
| **published_time** | **String** | Relative time string from source (e.g. &#x60;3 weeks ago&#x60;). |  |
| **is_live** | **Boolean** |  |  |
| **category** | **String** |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::YouTubeVideoPreview.new(
  id: null,
  title: null,
  author: null,
  channel_id: null,
  description: null,
  duration_seconds: null,
  view_count: null,
  published_time: null,
  is_live: null,
  category: null
)
```

