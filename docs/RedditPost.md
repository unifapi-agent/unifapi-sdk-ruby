# Unifapi::RedditPost

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | Reddit post id (&#x60;t3_*&#x60; fullname). |  |
| **title** | **String** |  |  |
| **url** | **String** | Permalink (or the linked URL for link posts). |  |
| **text** | **String** | Markdown body for self/text posts; empty otherwise. |  |
| **domain** | **String** |  |  |
| **created_at** | **String** | Source ISO timestamp. |  |
| **is_nsfw** | **Boolean** |  |  |
| **is_spoiler** | **Boolean** |  |  |
| **is_locked** | **Boolean** |  |  |
| **is_stickied** | **Boolean** |  |  |
| **subreddit** | [**RedditPostSubreddit**](RedditPostSubreddit.md) |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::RedditPost.new(
  id: null,
  title: null,
  url: null,
  text: null,
  domain: null,
  created_at: null,
  is_nsfw: null,
  is_spoiler: null,
  is_locked: null,
  is_stickied: null,
  subreddit: null
)
```

