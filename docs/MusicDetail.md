# Unifapi::MusicDetail

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **title** | **String** |  |  |
| **author** | **String** |  |  |
| **cover_url** | **String** |  |  |
| **duration** | **Float** | Seconds |  |
| **is_original** | **Boolean** |  |  |
| **play_url** | **String** |  |  |
| **user_count** | **Integer** | Number of videos that used this music |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::MusicDetail.new(
  id: null,
  title: null,
  author: null,
  cover_url: null,
  duration: null,
  is_original: null,
  play_url: null,
  user_count: null
)
```

