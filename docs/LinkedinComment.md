# Unifapi::LinkedinComment

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **urn** | **String** |  |  |
| **text** | **String** |  |  |
| **create_time** | **Integer** |  |  |
| **created_at** | **String** |  |  |
| **like_count** | **Integer** |  |  |
| **reply_count** | **Integer** |  |  |
| **is_pinned** | **Boolean** |  |  |
| **is_edited** | **Boolean** |  |  |
| **is_author** | **Boolean** |  |  |
| **has_previous_replies** | **Boolean** |  |  |
| **previous_replies_token** | **String** |  |  |
| **reactions** | [**Array&lt;LinkedinPostReactionsInner&gt;**](LinkedinPostReactionsInner.md) |  |  |
| **commenter** | [**LinkedinCommentCommenter**](LinkedinCommentCommenter.md) |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::LinkedinComment.new(
  id: null,
  urn: null,
  text: null,
  create_time: null,
  created_at: null,
  like_count: null,
  reply_count: null,
  is_pinned: null,
  is_edited: null,
  is_author: null,
  has_previous_replies: null,
  previous_replies_token: null,
  reactions: null,
  commenter: null
)
```

