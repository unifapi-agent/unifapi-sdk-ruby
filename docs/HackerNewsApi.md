# Unifapi::HackerNewsApi

All URIs are relative to *https://api.unifapi.com*

| Method | HTTP request | Description |
| ------ | ------------ | ----------- |
| [**hacker_news_items_id_get**](HackerNewsApi.md#hacker_news_items_id_get) | **GET** /hacker-news/items/{id} | Get Hacker News item by ID |
| [**hacker_news_max_item_get**](HackerNewsApi.md#hacker_news_max_item_get) | **GET** /hacker-news/max-item | Get largest Hacker News item ID |
| [**hacker_news_stories_feed_get**](HackerNewsApi.md#hacker_news_stories_feed_get) | **GET** /hacker-news/stories/{feed} | List Hacker News story IDs |
| [**hacker_news_stories_feed_items_get**](HackerNewsApi.md#hacker_news_stories_feed_items_get) | **GET** /hacker-news/stories/{feed}/items | List Hacker News story items |
| [**hacker_news_updates_get**](HackerNewsApi.md#hacker_news_updates_get) | **GET** /hacker-news/updates | Get changed Hacker News items and profiles |
| [**hacker_news_users_id_get**](HackerNewsApi.md#hacker_news_users_id_get) | **GET** /hacker-news/users/{id} | Get Hacker News user by ID |


## hacker_news_items_id_get

> <HackerNewsItemsIdGet200Response> hacker_news_items_id_get(id)

Get Hacker News item by ID

Fetch a single Hacker News item. Stories, comments, jobs, polls, and poll options share the same item shape.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::HackerNewsApi.new
id = 56 # Integer | Hacker News item id.

begin
  # Get Hacker News item by ID
  result = api_instance.hacker_news_items_id_get(id)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling HackerNewsApi->hacker_news_items_id_get: #{e}"
end
```

#### Using the hacker_news_items_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<HackerNewsItemsIdGet200Response>, Integer, Hash)> hacker_news_items_id_get_with_http_info(id)

```ruby
begin
  # Get Hacker News item by ID
  data, status_code, headers = api_instance.hacker_news_items_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <HackerNewsItemsIdGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling HackerNewsApi->hacker_news_items_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | Hacker News item id. |  |

### Return type

[**HackerNewsItemsIdGet200Response**](HackerNewsItemsIdGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## hacker_news_max_item_get

> <HackerNewsMaxItemGet200Response> hacker_news_max_item_get

Get largest Hacker News item ID

Returns the current largest Hacker News item id.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::HackerNewsApi.new

begin
  # Get largest Hacker News item ID
  result = api_instance.hacker_news_max_item_get
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling HackerNewsApi->hacker_news_max_item_get: #{e}"
end
```

#### Using the hacker_news_max_item_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<HackerNewsMaxItemGet200Response>, Integer, Hash)> hacker_news_max_item_get_with_http_info

```ruby
begin
  # Get largest Hacker News item ID
  data, status_code, headers = api_instance.hacker_news_max_item_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <HackerNewsMaxItemGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling HackerNewsApi->hacker_news_max_item_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**HackerNewsMaxItemGet200Response**](HackerNewsMaxItemGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## hacker_news_stories_feed_get

> <HackerNewsStoriesFeedGet200Response> hacker_news_stories_feed_get(feed, opts)

List Hacker News story IDs

List Hacker News story ids from a named feed. Use `/hacker-news/items/{id}` to fetch item details.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::HackerNewsApi.new
feed = Unifapi::HackerNewsStoryFeed::TOP # HackerNewsStoryFeed | Story feed: top, new, best, ask, show, or jobs.
opts = {
  cursor: 'cursor_example', # String | Zero-based offset cursor returned as `next_cursor`.
  limit: 56 # Integer | 
}

begin
  # List Hacker News story IDs
  result = api_instance.hacker_news_stories_feed_get(feed, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling HackerNewsApi->hacker_news_stories_feed_get: #{e}"
end
```

#### Using the hacker_news_stories_feed_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<HackerNewsStoriesFeedGet200Response>, Integer, Hash)> hacker_news_stories_feed_get_with_http_info(feed, opts)

```ruby
begin
  # List Hacker News story IDs
  data, status_code, headers = api_instance.hacker_news_stories_feed_get_with_http_info(feed, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <HackerNewsStoriesFeedGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling HackerNewsApi->hacker_news_stories_feed_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **feed** | [**HackerNewsStoryFeed**](.md) | Story feed: top, new, best, ask, show, or jobs. |  |
| **cursor** | **String** | Zero-based offset cursor returned as &#x60;next_cursor&#x60;. | [optional] |
| **limit** | **Integer** |  | [optional][default to 100] |

### Return type

[**HackerNewsStoriesFeedGet200Response**](HackerNewsStoriesFeedGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## hacker_news_stories_feed_items_get

> <HackerNewsStoriesFeedItemsGet200Response> hacker_news_stories_feed_items_get(feed, opts)

List Hacker News story items

Fetch item details from a named Hacker News story feed in one operation. Use this when an agent needs readable story titles, URLs, scores, authors, or comment counts.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::HackerNewsApi.new
feed = Unifapi::HackerNewsStoryFeed::TOP # HackerNewsStoryFeed | Story feed: top, new, best, ask, show, or jobs.
opts = {
  cursor: 'cursor_example', # String | Zero-based offset cursor returned as `next_cursor`.
  limit: 56 # Integer | 
}

begin
  # List Hacker News story items
  result = api_instance.hacker_news_stories_feed_items_get(feed, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling HackerNewsApi->hacker_news_stories_feed_items_get: #{e}"
end
```

#### Using the hacker_news_stories_feed_items_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<HackerNewsStoriesFeedItemsGet200Response>, Integer, Hash)> hacker_news_stories_feed_items_get_with_http_info(feed, opts)

```ruby
begin
  # List Hacker News story items
  data, status_code, headers = api_instance.hacker_news_stories_feed_items_get_with_http_info(feed, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <HackerNewsStoriesFeedItemsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling HackerNewsApi->hacker_news_stories_feed_items_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **feed** | [**HackerNewsStoryFeed**](.md) | Story feed: top, new, best, ask, show, or jobs. |  |
| **cursor** | **String** | Zero-based offset cursor returned as &#x60;next_cursor&#x60;. | [optional] |
| **limit** | **Integer** |  | [optional][default to 20] |

### Return type

[**HackerNewsStoriesFeedItemsGet200Response**](HackerNewsStoriesFeedItemsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## hacker_news_updates_get

> <HackerNewsUpdatesGet200Response> hacker_news_updates_get

Get changed Hacker News items and profiles

Returns recently changed Hacker News item ids and user profile ids.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::HackerNewsApi.new

begin
  # Get changed Hacker News items and profiles
  result = api_instance.hacker_news_updates_get
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling HackerNewsApi->hacker_news_updates_get: #{e}"
end
```

#### Using the hacker_news_updates_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<HackerNewsUpdatesGet200Response>, Integer, Hash)> hacker_news_updates_get_with_http_info

```ruby
begin
  # Get changed Hacker News items and profiles
  data, status_code, headers = api_instance.hacker_news_updates_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <HackerNewsUpdatesGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling HackerNewsApi->hacker_news_updates_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**HackerNewsUpdatesGet200Response**](HackerNewsUpdatesGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## hacker_news_users_id_get

> <HackerNewsUsersIdGet200Response> hacker_news_users_id_get(id)

Get Hacker News user by ID

Fetch a public Hacker News user profile by case-sensitive username.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::HackerNewsApi.new
id = 'id_example' # String | Case-sensitive Hacker News username.

begin
  # Get Hacker News user by ID
  result = api_instance.hacker_news_users_id_get(id)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling HackerNewsApi->hacker_news_users_id_get: #{e}"
end
```

#### Using the hacker_news_users_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<HackerNewsUsersIdGet200Response>, Integer, Hash)> hacker_news_users_id_get_with_http_info(id)

```ruby
begin
  # Get Hacker News user by ID
  data, status_code, headers = api_instance.hacker_news_users_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <HackerNewsUsersIdGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling HackerNewsApi->hacker_news_users_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | Case-sensitive Hacker News username. |  |

### Return type

[**HackerNewsUsersIdGet200Response**](HackerNewsUsersIdGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

