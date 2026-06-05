# Unifapi::HackerNewsItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **deleted** | **Boolean** |  | [optional] |
| **type** | [**HackerNewsItemType**](HackerNewsItemType.md) |  | [optional] |
| **by** | **String** |  | [optional] |
| **time** | **Integer** | Unix epoch seconds | [optional] |
| **text** | **String** | HTML text for comments, stories, polls, and jobs. | [optional] |
| **dead** | **Boolean** |  | [optional] |
| **parent** | **Integer** |  | [optional] |
| **poll** | **Integer** |  | [optional] |
| **kids** | **Array&lt;Integer&gt;** |  | [optional] |
| **url** | **String** |  | [optional] |
| **score** | **Integer** |  | [optional] |
| **title** | **String** | HTML title for stories, polls, and jobs. | [optional] |
| **parts** | **Array&lt;Integer&gt;** |  | [optional] |
| **descendants** | **Integer** |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::HackerNewsItem.new(
  id: null,
  deleted: null,
  type: null,
  by: null,
  time: null,
  text: null,
  dead: null,
  parent: null,
  poll: null,
  kids: null,
  url: null,
  score: null,
  title: null,
  parts: null,
  descendants: null
)
```

