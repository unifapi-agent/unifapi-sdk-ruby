# Unifapi::Video

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **title** | **String** | Per ADR 0004 Rule 6: TikTok title is the video description. |  |
| **video_description** | **String** |  |  |
| **create_time** | **Integer** | Unix epoch seconds |  |
| **duration** | **Float** | Seconds |  |
| **cover_image_url** | **String** |  |  |
| **share_url** | **String** | Tracking-param-stripped canonical URL |  |
| **embed_link** | **String** |  |  |
| **width** | **Integer** |  |  |
| **height** | **Integer** |  |  |
| **like_count** | **Integer** |  |  |
| **comment_count** | **Integer** |  |  |
| **share_count** | **Integer** |  |  |
| **view_count** | **Integer** |  |  |
| **author** | [**Author**](Author.md) |  |  |
| **region** | **String** |  |  |
| **hashtags** | **Array&lt;String&gt;** |  |  |
| **music** | [**Music**](Music.md) |  |  |
| **is_image_post** | **Boolean** |  |  |
| **play_url** | **String** |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::Video.new(
  id: null,
  title: null,
  video_description: null,
  create_time: null,
  duration: null,
  cover_image_url: null,
  share_url: null,
  embed_link: null,
  width: null,
  height: null,
  like_count: null,
  comment_count: null,
  share_count: null,
  view_count: null,
  author: null,
  region: null,
  hashtags: null,
  music: null,
  is_image_post: null,
  play_url: null
)
```

