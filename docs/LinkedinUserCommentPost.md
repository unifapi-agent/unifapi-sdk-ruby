# Unifapi::LinkedinUserCommentPost

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **share_urn** | **String** |  |  |
| **post_type** | **String** | ugc | activity | share | ... |  |
| **text** | **String** |  |  |
| **url** | **String** |  |  |
| **create_time** | **Integer** | Unix epoch seconds |  |
| **created_at** | **String** | Original ISO timestamp |  |
| **like_count** | **Integer** |  |  |
| **comment_count** | **Integer** |  |  |
| **share_count** | **Integer** |  |  |
| **reactions** | [**Array&lt;LinkedinPostReactionsInner&gt;**](LinkedinPostReactionsInner.md) |  |  |
| **author** | [**LinkedinPostAuthor**](LinkedinPostAuthor.md) |  |  |
| **content** | **Hash&lt;String, Object&gt;** | Pass-through LinkedIn post body block (images, video, document, article, celebration, poll, event). LinkedIn&#39;s structure for each is complex and evolving — kept as-is rather than reshaped. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::LinkedinUserCommentPost.new(
  id: null,
  share_urn: null,
  post_type: null,
  text: null,
  url: null,
  create_time: null,
  created_at: null,
  like_count: null,
  comment_count: null,
  share_count: null,
  reactions: null,
  author: null,
  content: null
)
```

