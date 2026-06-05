# Unifapi::RedditApi

All URIs are relative to *https://api.unifapi.com*

| Method | HTTP request | Description |
| ------ | ------------ | ----------- |
| [**reddit_feed_home_get**](RedditApi.md#reddit_feed_home_get) | **GET** /reddit/feed/home | Browse Reddit&#39;s anonymous home feed |
| [**reddit_feed_news_get**](RedditApi.md#reddit_feed_news_get) | **GET** /reddit/feed/news | Browse Reddit&#39;s news feed |
| [**reddit_feed_popular_get**](RedditApi.md#reddit_feed_popular_get) | **GET** /reddit/feed/popular | Browse Reddit&#39;s popular feed |
| [**reddit_posts_id_comments_get**](RedditApi.md#reddit_posts_id_comments_get) | **GET** /reddit/posts/{id}/comments | List Reddit comments on a post |
| [**reddit_posts_id_get**](RedditApi.md#reddit_posts_id_get) | **GET** /reddit/posts/{id} | Get a Reddit post by id |
| [**reddit_subreddits_name_get**](RedditApi.md#reddit_subreddits_name_get) | **GET** /reddit/subreddits/{name} | Get a Reddit subreddit by name |
| [**reddit_trending_searches_get**](RedditApi.md#reddit_trending_searches_get) | **GET** /reddit/trending-searches | List Reddit&#39;s current trending search queries |
| [**reddit_users_username_comments_get**](RedditApi.md#reddit_users_username_comments_get) | **GET** /reddit/users/{username}/comments | List Reddit comments authored by a user |
| [**reddit_users_username_get**](RedditApi.md#reddit_users_username_get) | **GET** /reddit/users/{username} | Get a Reddit user profile by username |
| [**reddit_users_username_posts_get**](RedditApi.md#reddit_users_username_posts_get) | **GET** /reddit/users/{username}/posts | List Reddit posts authored by a user |


## reddit_feed_home_get

> <RedditFeedHomeGet200Response> reddit_feed_home_get(opts)

Browse Reddit's anonymous home feed

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::RedditApi.new
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # Browse Reddit's anonymous home feed
  result = api_instance.reddit_feed_home_get(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling RedditApi->reddit_feed_home_get: #{e}"
end
```

#### Using the reddit_feed_home_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<RedditFeedHomeGet200Response>, Integer, Hash)> reddit_feed_home_get_with_http_info(opts)

```ruby
begin
  # Browse Reddit's anonymous home feed
  data, status_code, headers = api_instance.reddit_feed_home_get_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <RedditFeedHomeGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling RedditApi->reddit_feed_home_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **cursor** | **String** |  | [optional] |

### Return type

[**RedditFeedHomeGet200Response**](RedditFeedHomeGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## reddit_feed_news_get

> <RedditFeedHomeGet200Response> reddit_feed_news_get(opts)

Browse Reddit's news feed

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::RedditApi.new
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # Browse Reddit's news feed
  result = api_instance.reddit_feed_news_get(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling RedditApi->reddit_feed_news_get: #{e}"
end
```

#### Using the reddit_feed_news_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<RedditFeedHomeGet200Response>, Integer, Hash)> reddit_feed_news_get_with_http_info(opts)

```ruby
begin
  # Browse Reddit's news feed
  data, status_code, headers = api_instance.reddit_feed_news_get_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <RedditFeedHomeGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling RedditApi->reddit_feed_news_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **cursor** | **String** |  | [optional] |

### Return type

[**RedditFeedHomeGet200Response**](RedditFeedHomeGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## reddit_feed_popular_get

> <RedditFeedHomeGet200Response> reddit_feed_popular_get(opts)

Browse Reddit's popular feed

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::RedditApi.new
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # Browse Reddit's popular feed
  result = api_instance.reddit_feed_popular_get(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling RedditApi->reddit_feed_popular_get: #{e}"
end
```

#### Using the reddit_feed_popular_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<RedditFeedHomeGet200Response>, Integer, Hash)> reddit_feed_popular_get_with_http_info(opts)

```ruby
begin
  # Browse Reddit's popular feed
  data, status_code, headers = api_instance.reddit_feed_popular_get_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <RedditFeedHomeGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling RedditApi->reddit_feed_popular_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **cursor** | **String** |  | [optional] |

### Return type

[**RedditFeedHomeGet200Response**](RedditFeedHomeGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## reddit_posts_id_comments_get

> <RedditPostsIdCommentsGet200Response> reddit_posts_id_comments_get(id, opts)

List Reddit comments on a post

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::RedditApi.new
id = 'id_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List Reddit comments on a post
  result = api_instance.reddit_posts_id_comments_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling RedditApi->reddit_posts_id_comments_get: #{e}"
end
```

#### Using the reddit_posts_id_comments_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<RedditPostsIdCommentsGet200Response>, Integer, Hash)> reddit_posts_id_comments_get_with_http_info(id, opts)

```ruby
begin
  # List Reddit comments on a post
  data, status_code, headers = api_instance.reddit_posts_id_comments_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <RedditPostsIdCommentsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling RedditApi->reddit_posts_id_comments_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**RedditPostsIdCommentsGet200Response**](RedditPostsIdCommentsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## reddit_posts_id_get

> <RedditPostsIdGet200Response> reddit_posts_id_get(id)

Get a Reddit post by id

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::RedditApi.new
id = 'id_example' # String | Reddit post fullname, e.g. `t3_1thjm1o`.

begin
  # Get a Reddit post by id
  result = api_instance.reddit_posts_id_get(id)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling RedditApi->reddit_posts_id_get: #{e}"
end
```

#### Using the reddit_posts_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<RedditPostsIdGet200Response>, Integer, Hash)> reddit_posts_id_get_with_http_info(id)

```ruby
begin
  # Get a Reddit post by id
  data, status_code, headers = api_instance.reddit_posts_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <RedditPostsIdGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling RedditApi->reddit_posts_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | Reddit post fullname, e.g. &#x60;t3_1thjm1o&#x60;. |  |

### Return type

[**RedditPostsIdGet200Response**](RedditPostsIdGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## reddit_subreddits_name_get

> <RedditSubredditsNameGet200Response> reddit_subreddits_name_get(name)

Get a Reddit subreddit by name

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::RedditApi.new
name = 'name_example' # String | Subreddit slug without `r/`, e.g. `pics`.

begin
  # Get a Reddit subreddit by name
  result = api_instance.reddit_subreddits_name_get(name)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling RedditApi->reddit_subreddits_name_get: #{e}"
end
```

#### Using the reddit_subreddits_name_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<RedditSubredditsNameGet200Response>, Integer, Hash)> reddit_subreddits_name_get_with_http_info(name)

```ruby
begin
  # Get a Reddit subreddit by name
  data, status_code, headers = api_instance.reddit_subreddits_name_get_with_http_info(name)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <RedditSubredditsNameGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling RedditApi->reddit_subreddits_name_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | Subreddit slug without &#x60;r/&#x60;, e.g. &#x60;pics&#x60;. |  |

### Return type

[**RedditSubredditsNameGet200Response**](RedditSubredditsNameGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## reddit_trending_searches_get

> <RedditTrendingSearchesGet200Response> reddit_trending_searches_get

List Reddit's current trending search queries

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::RedditApi.new

begin
  # List Reddit's current trending search queries
  result = api_instance.reddit_trending_searches_get
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling RedditApi->reddit_trending_searches_get: #{e}"
end
```

#### Using the reddit_trending_searches_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<RedditTrendingSearchesGet200Response>, Integer, Hash)> reddit_trending_searches_get_with_http_info

```ruby
begin
  # List Reddit's current trending search queries
  data, status_code, headers = api_instance.reddit_trending_searches_get_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <RedditTrendingSearchesGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling RedditApi->reddit_trending_searches_get_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**RedditTrendingSearchesGet200Response**](RedditTrendingSearchesGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## reddit_users_username_comments_get

> <RedditPostsIdCommentsGet200Response> reddit_users_username_comments_get(username, opts)

List Reddit comments authored by a user

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::RedditApi.new
username = 'username_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List Reddit comments authored by a user
  result = api_instance.reddit_users_username_comments_get(username, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling RedditApi->reddit_users_username_comments_get: #{e}"
end
```

#### Using the reddit_users_username_comments_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<RedditPostsIdCommentsGet200Response>, Integer, Hash)> reddit_users_username_comments_get_with_http_info(username, opts)

```ruby
begin
  # List Reddit comments authored by a user
  data, status_code, headers = api_instance.reddit_users_username_comments_get_with_http_info(username, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <RedditPostsIdCommentsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling RedditApi->reddit_users_username_comments_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**RedditPostsIdCommentsGet200Response**](RedditPostsIdCommentsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## reddit_users_username_get

> <RedditUsersUsernameGet200Response> reddit_users_username_get(username)

Get a Reddit user profile by username

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::RedditApi.new
username = 'username_example' # String | 

begin
  # Get a Reddit user profile by username
  result = api_instance.reddit_users_username_get(username)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling RedditApi->reddit_users_username_get: #{e}"
end
```

#### Using the reddit_users_username_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<RedditUsersUsernameGet200Response>, Integer, Hash)> reddit_users_username_get_with_http_info(username)

```ruby
begin
  # Get a Reddit user profile by username
  data, status_code, headers = api_instance.reddit_users_username_get_with_http_info(username)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <RedditUsersUsernameGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling RedditApi->reddit_users_username_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |

### Return type

[**RedditUsersUsernameGet200Response**](RedditUsersUsernameGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## reddit_users_username_posts_get

> <RedditFeedHomeGet200Response> reddit_users_username_posts_get(username, opts)

List Reddit posts authored by a user

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::RedditApi.new
username = 'username_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List Reddit posts authored by a user
  result = api_instance.reddit_users_username_posts_get(username, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling RedditApi->reddit_users_username_posts_get: #{e}"
end
```

#### Using the reddit_users_username_posts_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<RedditFeedHomeGet200Response>, Integer, Hash)> reddit_users_username_posts_get_with_http_info(username, opts)

```ruby
begin
  # List Reddit posts authored by a user
  data, status_code, headers = api_instance.reddit_users_username_posts_get_with_http_info(username, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <RedditFeedHomeGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling RedditApi->reddit_users_username_posts_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**RedditFeedHomeGet200Response**](RedditFeedHomeGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

