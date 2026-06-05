# Unifapi::XTweet

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **text** | **String** |  |  |
| **author_id** | **String** |  | [optional] |
| **created_at** | **String** |  | [optional] |
| **conversation_id** | **String** |  | [optional] |
| **lang** | **String** |  | [optional] |
| **possibly_sensitive** | **Boolean** |  | [optional] |
| **public_metrics** | [**XPublicMetrics**](XPublicMetrics.md) |  | [optional] |
| **attachments** | [**XTweetAttachments**](XTweetAttachments.md) |  | [optional] |
| **edit_history_tweet_ids** | **Array&lt;String&gt;** |  | [optional] |
| **author** | [**XUser**](XUser.md) |  | [optional] |
| **media** | [**Array&lt;XMedia&gt;**](XMedia.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::XTweet.new(
  id: null,
  text: null,
  author_id: null,
  created_at: null,
  conversation_id: null,
  lang: null,
  possibly_sensitive: null,
  public_metrics: null,
  attachments: null,
  edit_history_tweet_ids: null,
  author: null,
  media: null
)
```

