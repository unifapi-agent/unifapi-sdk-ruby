# Unifapi::RedditSubreddit

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | Subreddit slug (URL form without &#x60;r/&#x60;). |  |
| **subreddit_t5_id** | **String** | Reddit internal subreddit id (&#x60;t5_*&#x60; fullname). |  |
| **name** | **String** |  |  |
| **prefixed_name** | **String** | Display form like &#x60;r/pics&#x60;. |  |
| **title** | **String** |  |  |
| **description** | **String** |  |  |
| **subscribers_count** | **Float** |  |  |
| **active_count** | **Float** |  |  |
| **is_nsfw** | **Boolean** |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::RedditSubreddit.new(
  id: null,
  subreddit_t5_id: null,
  name: null,
  prefixed_name: null,
  title: null,
  description: null,
  subscribers_count: null,
  active_count: null,
  is_nsfw: null
)
```

