# Unifapi::TiktokApi

All URIs are relative to *https://api.unifapi.com*

| Method | HTTP request | Description |
| ------ | ------------ | ----------- |
| [**tiktok_feed_recommended_post**](TiktokApi.md#tiktok_feed_recommended_post) | **POST** /tiktok/feed/recommended | Get TikTok recommendation videos |
| [**tiktok_hashtags_id_get**](TiktokApi.md#tiktok_hashtags_id_get) | **GET** /tiktok/hashtags/{id} | Get a TikTok hashtag by ID |
| [**tiktok_hashtags_id_videos_get**](TiktokApi.md#tiktok_hashtags_id_videos_get) | **GET** /tiktok/hashtags/{id}/videos | List videos tagged with a TikTok hashtag |
| [**tiktok_music_id_get**](TiktokApi.md#tiktok_music_id_get) | **GET** /tiktok/music/{id} | Get a TikTok music track by ID |
| [**tiktok_music_id_videos_get**](TiktokApi.md#tiktok_music_id_videos_get) | **GET** /tiktok/music/{id}/videos | List videos using a TikTok music track |
| [**tiktok_search_get**](TiktokApi.md#tiktok_search_get) | **GET** /tiktok/search | General TikTok search (returns videos) |
| [**tiktok_search_hashtags_get**](TiktokApi.md#tiktok_search_hashtags_get) | **GET** /tiktok/search/hashtags | Search TikTok hashtags by keyword |
| [**tiktok_search_users_get**](TiktokApi.md#tiktok_search_users_get) | **GET** /tiktok/search/users | Search TikTok users by keyword |
| [**tiktok_search_videos_get**](TiktokApi.md#tiktok_search_videos_get) | **GET** /tiktok/search/videos | Search TikTok videos by keyword |
| [**tiktok_users_id_followers_get**](TiktokApi.md#tiktok_users_id_followers_get) | **GET** /tiktok/users/{id}/followers | List a TikTok user&#39;s followers |
| [**tiktok_users_id_following_get**](TiktokApi.md#tiktok_users_id_following_get) | **GET** /tiktok/users/{id}/following | List users a TikTok user is following |
| [**tiktok_users_id_get**](TiktokApi.md#tiktok_users_id_get) | **GET** /tiktok/users/{id} | Get a TikTok user profile |
| [**tiktok_users_id_likes_get**](TiktokApi.md#tiktok_users_id_likes_get) | **GET** /tiktok/users/{id}/likes | List videos liked by a TikTok user |
| [**tiktok_users_id_videos_get**](TiktokApi.md#tiktok_users_id_videos_get) | **GET** /tiktok/users/{id}/videos | List videos posted by a TikTok user |
| [**tiktok_users_resolve_get**](TiktokApi.md#tiktok_users_resolve_get) | **GET** /tiktok/users/resolve | Resolve a TikTok username to a user id |
| [**tiktok_videos_batch_post**](TiktokApi.md#tiktok_videos_batch_post) | **POST** /tiktok/videos/batch | Batch-fetch TikTok videos by ID |
| [**tiktok_videos_id_comments_comment_id_replies_get**](TiktokApi.md#tiktok_videos_id_comments_comment_id_replies_get) | **GET** /tiktok/videos/{id}/comments/{comment_id}/replies | List replies to a TikTok comment |
| [**tiktok_videos_id_comments_get**](TiktokApi.md#tiktok_videos_id_comments_get) | **GET** /tiktok/videos/{id}/comments | List top-level comments on a TikTok video |
| [**tiktok_videos_id_get**](TiktokApi.md#tiktok_videos_id_get) | **GET** /tiktok/videos/{id} | Get a TikTok video by ID |
| [**tiktok_videos_resolve_get**](TiktokApi.md#tiktok_videos_resolve_get) | **GET** /tiktok/videos/resolve | Resolve a TikTok share URL to a video |


## tiktok_feed_recommended_post

> <TiktokFeedRecommendedPost200Response> tiktok_feed_recommended_post(opts)

Get TikTok recommendation videos

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::TiktokApi.new
opts = {
  tiktok_feed_recommended_post_request: Unifapi::TiktokFeedRecommendedPostRequest.new # TiktokFeedRecommendedPostRequest | 
}

begin
  # Get TikTok recommendation videos
  result = api_instance.tiktok_feed_recommended_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_feed_recommended_post: #{e}"
end
```

#### Using the tiktok_feed_recommended_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<TiktokFeedRecommendedPost200Response>, Integer, Hash)> tiktok_feed_recommended_post_with_http_info(opts)

```ruby
begin
  # Get TikTok recommendation videos
  data, status_code, headers = api_instance.tiktok_feed_recommended_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <TiktokFeedRecommendedPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_feed_recommended_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **tiktok_feed_recommended_post_request** | [**TiktokFeedRecommendedPostRequest**](TiktokFeedRecommendedPostRequest.md) |  | [optional] |

### Return type

[**TiktokFeedRecommendedPost200Response**](TiktokFeedRecommendedPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## tiktok_hashtags_id_get

> <TiktokHashtagsIdGet200Response> tiktok_hashtags_id_get(id)

Get a TikTok hashtag by ID

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::TiktokApi.new
id = 'id_example' # String | 

begin
  # Get a TikTok hashtag by ID
  result = api_instance.tiktok_hashtags_id_get(id)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_hashtags_id_get: #{e}"
end
```

#### Using the tiktok_hashtags_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<TiktokHashtagsIdGet200Response>, Integer, Hash)> tiktok_hashtags_id_get_with_http_info(id)

```ruby
begin
  # Get a TikTok hashtag by ID
  data, status_code, headers = api_instance.tiktok_hashtags_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <TiktokHashtagsIdGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_hashtags_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**TiktokHashtagsIdGet200Response**](TiktokHashtagsIdGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## tiktok_hashtags_id_videos_get

> <TiktokHashtagsIdVideosGet200Response> tiktok_hashtags_id_videos_get(id, opts)

List videos tagged with a TikTok hashtag

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::TiktokApi.new
id = 'id_example' # String | 
opts = {
  cursor: 'cursor_example', # String | 
  limit: 56 # Integer | 
}

begin
  # List videos tagged with a TikTok hashtag
  result = api_instance.tiktok_hashtags_id_videos_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_hashtags_id_videos_get: #{e}"
end
```

#### Using the tiktok_hashtags_id_videos_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<TiktokHashtagsIdVideosGet200Response>, Integer, Hash)> tiktok_hashtags_id_videos_get_with_http_info(id, opts)

```ruby
begin
  # List videos tagged with a TikTok hashtag
  data, status_code, headers = api_instance.tiktok_hashtags_id_videos_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <TiktokHashtagsIdVideosGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_hashtags_id_videos_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **cursor** | **String** |  | [optional] |
| **limit** | **Integer** |  | [optional][default to 20] |

### Return type

[**TiktokHashtagsIdVideosGet200Response**](TiktokHashtagsIdVideosGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## tiktok_music_id_get

> <TiktokMusicIdGet200Response> tiktok_music_id_get(id)

Get a TikTok music track by ID

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::TiktokApi.new
id = 'id_example' # String | 

begin
  # Get a TikTok music track by ID
  result = api_instance.tiktok_music_id_get(id)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_music_id_get: #{e}"
end
```

#### Using the tiktok_music_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<TiktokMusicIdGet200Response>, Integer, Hash)> tiktok_music_id_get_with_http_info(id)

```ruby
begin
  # Get a TikTok music track by ID
  data, status_code, headers = api_instance.tiktok_music_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <TiktokMusicIdGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_music_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**TiktokMusicIdGet200Response**](TiktokMusicIdGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## tiktok_music_id_videos_get

> <TiktokHashtagsIdVideosGet200Response> tiktok_music_id_videos_get(id, opts)

List videos using a TikTok music track

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::TiktokApi.new
id = 'id_example' # String | 
opts = {
  cursor: 'cursor_example', # String | 
  limit: 56 # Integer | 
}

begin
  # List videos using a TikTok music track
  result = api_instance.tiktok_music_id_videos_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_music_id_videos_get: #{e}"
end
```

#### Using the tiktok_music_id_videos_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<TiktokHashtagsIdVideosGet200Response>, Integer, Hash)> tiktok_music_id_videos_get_with_http_info(id, opts)

```ruby
begin
  # List videos using a TikTok music track
  data, status_code, headers = api_instance.tiktok_music_id_videos_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <TiktokHashtagsIdVideosGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_music_id_videos_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **cursor** | **String** |  | [optional] |
| **limit** | **Integer** |  | [optional][default to 20] |

### Return type

[**TiktokHashtagsIdVideosGet200Response**](TiktokHashtagsIdVideosGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## tiktok_search_get

> <TiktokHashtagsIdVideosGet200Response> tiktok_search_get(q, opts)

General TikTok search (returns videos)

Returns TikTok videos for the keyword `q`. Use type-specific endpoints when needed.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::TiktokApi.new
q = 'q_example' # String | Search keyword
opts = {
  cursor: 'cursor_example', # String | 
  limit: 56 # Integer | 
}

begin
  # General TikTok search (returns videos)
  result = api_instance.tiktok_search_get(q, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_search_get: #{e}"
end
```

#### Using the tiktok_search_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<TiktokHashtagsIdVideosGet200Response>, Integer, Hash)> tiktok_search_get_with_http_info(q, opts)

```ruby
begin
  # General TikTok search (returns videos)
  data, status_code, headers = api_instance.tiktok_search_get_with_http_info(q, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <TiktokHashtagsIdVideosGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_search_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **q** | **String** | Search keyword |  |
| **cursor** | **String** |  | [optional] |
| **limit** | **Integer** |  | [optional][default to 20] |

### Return type

[**TiktokHashtagsIdVideosGet200Response**](TiktokHashtagsIdVideosGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## tiktok_search_hashtags_get

> <TiktokSearchHashtagsGet200Response> tiktok_search_hashtags_get(q, opts)

Search TikTok hashtags by keyword

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::TiktokApi.new
q = 'q_example' # String | Search keyword
opts = {
  cursor: 'cursor_example', # String | 
  limit: 56 # Integer | 
}

begin
  # Search TikTok hashtags by keyword
  result = api_instance.tiktok_search_hashtags_get(q, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_search_hashtags_get: #{e}"
end
```

#### Using the tiktok_search_hashtags_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<TiktokSearchHashtagsGet200Response>, Integer, Hash)> tiktok_search_hashtags_get_with_http_info(q, opts)

```ruby
begin
  # Search TikTok hashtags by keyword
  data, status_code, headers = api_instance.tiktok_search_hashtags_get_with_http_info(q, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <TiktokSearchHashtagsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_search_hashtags_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **q** | **String** | Search keyword |  |
| **cursor** | **String** |  | [optional] |
| **limit** | **Integer** |  | [optional][default to 20] |

### Return type

[**TiktokSearchHashtagsGet200Response**](TiktokSearchHashtagsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## tiktok_search_users_get

> <TiktokSearchUsersGet200Response> tiktok_search_users_get(q, opts)

Search TikTok users by keyword

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::TiktokApi.new
q = 'q_example' # String | Search keyword
opts = {
  cursor: 'cursor_example', # String | 
  limit: 56 # Integer | 
}

begin
  # Search TikTok users by keyword
  result = api_instance.tiktok_search_users_get(q, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_search_users_get: #{e}"
end
```

#### Using the tiktok_search_users_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<TiktokSearchUsersGet200Response>, Integer, Hash)> tiktok_search_users_get_with_http_info(q, opts)

```ruby
begin
  # Search TikTok users by keyword
  data, status_code, headers = api_instance.tiktok_search_users_get_with_http_info(q, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <TiktokSearchUsersGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_search_users_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **q** | **String** | Search keyword |  |
| **cursor** | **String** |  | [optional] |
| **limit** | **Integer** |  | [optional][default to 20] |

### Return type

[**TiktokSearchUsersGet200Response**](TiktokSearchUsersGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## tiktok_search_videos_get

> <TiktokHashtagsIdVideosGet200Response> tiktok_search_videos_get(q, opts)

Search TikTok videos by keyword

Returns a paginated list of TikTok videos matching the keyword `q`. Use `next_cursor` from the response as the next request's `cursor`.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::TiktokApi.new
q = 'q_example' # String | Search keyword
opts = {
  cursor: 'cursor_example', # String | 
  limit: 56 # Integer | 
}

begin
  # Search TikTok videos by keyword
  result = api_instance.tiktok_search_videos_get(q, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_search_videos_get: #{e}"
end
```

#### Using the tiktok_search_videos_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<TiktokHashtagsIdVideosGet200Response>, Integer, Hash)> tiktok_search_videos_get_with_http_info(q, opts)

```ruby
begin
  # Search TikTok videos by keyword
  data, status_code, headers = api_instance.tiktok_search_videos_get_with_http_info(q, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <TiktokHashtagsIdVideosGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_search_videos_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **q** | **String** | Search keyword |  |
| **cursor** | **String** |  | [optional] |
| **limit** | **Integer** |  | [optional][default to 20] |

### Return type

[**TiktokHashtagsIdVideosGet200Response**](TiktokHashtagsIdVideosGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## tiktok_users_id_followers_get

> <TiktokSearchUsersGet200Response> tiktok_users_id_followers_get(id, opts)

List a TikTok user's followers

Returns a paginated list of users following the given user.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::TiktokApi.new
id = 'id_example' # String | TikTok sec_uid, numeric user id, or public handle.
opts = {
  cursor: 'cursor_example', # String | 
  limit: 56 # Integer | 
}

begin
  # List a TikTok user's followers
  result = api_instance.tiktok_users_id_followers_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_users_id_followers_get: #{e}"
end
```

#### Using the tiktok_users_id_followers_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<TiktokSearchUsersGet200Response>, Integer, Hash)> tiktok_users_id_followers_get_with_http_info(id, opts)

```ruby
begin
  # List a TikTok user's followers
  data, status_code, headers = api_instance.tiktok_users_id_followers_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <TiktokSearchUsersGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_users_id_followers_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | TikTok sec_uid, numeric user id, or public handle. |  |
| **cursor** | **String** |  | [optional] |
| **limit** | **Integer** |  | [optional][default to 20] |

### Return type

[**TiktokSearchUsersGet200Response**](TiktokSearchUsersGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## tiktok_users_id_following_get

> <TiktokSearchUsersGet200Response> tiktok_users_id_following_get(id, opts)

List users a TikTok user is following

Returns a paginated list of users the given user is following.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::TiktokApi.new
id = 'id_example' # String | TikTok sec_uid, numeric user id, or public handle.
opts = {
  cursor: 'cursor_example', # String | 
  limit: 56 # Integer | 
}

begin
  # List users a TikTok user is following
  result = api_instance.tiktok_users_id_following_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_users_id_following_get: #{e}"
end
```

#### Using the tiktok_users_id_following_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<TiktokSearchUsersGet200Response>, Integer, Hash)> tiktok_users_id_following_get_with_http_info(id, opts)

```ruby
begin
  # List users a TikTok user is following
  data, status_code, headers = api_instance.tiktok_users_id_following_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <TiktokSearchUsersGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_users_id_following_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | TikTok sec_uid, numeric user id, or public handle. |  |
| **cursor** | **String** |  | [optional] |
| **limit** | **Integer** |  | [optional][default to 20] |

### Return type

[**TiktokSearchUsersGet200Response**](TiktokSearchUsersGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## tiktok_users_id_get

> <TiktokUsersIdGet200Response> tiktok_users_id_get(id)

Get a TikTok user profile

Returns the canonicalized public profile for the TikTok user with the given sec_uid, numeric user id, or handle.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::TiktokApi.new
id = 'id_example' # String | TikTok sec_uid, numeric user id, or public handle.

begin
  # Get a TikTok user profile
  result = api_instance.tiktok_users_id_get(id)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_users_id_get: #{e}"
end
```

#### Using the tiktok_users_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<TiktokUsersIdGet200Response>, Integer, Hash)> tiktok_users_id_get_with_http_info(id)

```ruby
begin
  # Get a TikTok user profile
  data, status_code, headers = api_instance.tiktok_users_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <TiktokUsersIdGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_users_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | TikTok sec_uid, numeric user id, or public handle. |  |

### Return type

[**TiktokUsersIdGet200Response**](TiktokUsersIdGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## tiktok_users_id_likes_get

> <TiktokHashtagsIdVideosGet200Response> tiktok_users_id_likes_get(id, opts)

List videos liked by a TikTok user

Returns a paginated list of videos the user has liked where the user has made their likes public.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::TiktokApi.new
id = 'id_example' # String | TikTok sec_uid, numeric user id, or public handle.
opts = {
  cursor: 'cursor_example', # String | 
  limit: 56 # Integer | 
}

begin
  # List videos liked by a TikTok user
  result = api_instance.tiktok_users_id_likes_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_users_id_likes_get: #{e}"
end
```

#### Using the tiktok_users_id_likes_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<TiktokHashtagsIdVideosGet200Response>, Integer, Hash)> tiktok_users_id_likes_get_with_http_info(id, opts)

```ruby
begin
  # List videos liked by a TikTok user
  data, status_code, headers = api_instance.tiktok_users_id_likes_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <TiktokHashtagsIdVideosGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_users_id_likes_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | TikTok sec_uid, numeric user id, or public handle. |  |
| **cursor** | **String** |  | [optional] |
| **limit** | **Integer** |  | [optional][default to 20] |

### Return type

[**TiktokHashtagsIdVideosGet200Response**](TiktokHashtagsIdVideosGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## tiktok_users_id_videos_get

> <TiktokHashtagsIdVideosGet200Response> tiktok_users_id_videos_get(id, opts)

List videos posted by a TikTok user

Returns a paginated list of public videos posted by the user. Use `next_cursor` from the response as the next request's `cursor`.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::TiktokApi.new
id = 'id_example' # String | TikTok sec_uid, numeric user id, or public handle.
opts = {
  cursor: 'cursor_example', # String | 
  limit: 56 # Integer | 
}

begin
  # List videos posted by a TikTok user
  result = api_instance.tiktok_users_id_videos_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_users_id_videos_get: #{e}"
end
```

#### Using the tiktok_users_id_videos_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<TiktokHashtagsIdVideosGet200Response>, Integer, Hash)> tiktok_users_id_videos_get_with_http_info(id, opts)

```ruby
begin
  # List videos posted by a TikTok user
  data, status_code, headers = api_instance.tiktok_users_id_videos_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <TiktokHashtagsIdVideosGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_users_id_videos_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | TikTok sec_uid, numeric user id, or public handle. |  |
| **cursor** | **String** |  | [optional] |
| **limit** | **Integer** |  | [optional][default to 20] |

### Return type

[**TiktokHashtagsIdVideosGet200Response**](TiktokHashtagsIdVideosGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## tiktok_users_resolve_get

> <TiktokUsersResolveGet200Response> tiktok_users_resolve_get(username)

Resolve a TikTok username to a user id

Accepts a public TikTok username (handle) and returns the user's stable opaque id for other /tiktok/users/{id} endpoints.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::TiktokApi.new
username = 'username_example' # String | Public TikTok handle, e.g. 'jennmelon'

begin
  # Resolve a TikTok username to a user id
  result = api_instance.tiktok_users_resolve_get(username)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_users_resolve_get: #{e}"
end
```

#### Using the tiktok_users_resolve_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<TiktokUsersResolveGet200Response>, Integer, Hash)> tiktok_users_resolve_get_with_http_info(username)

```ruby
begin
  # Resolve a TikTok username to a user id
  data, status_code, headers = api_instance.tiktok_users_resolve_get_with_http_info(username)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <TiktokUsersResolveGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_users_resolve_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** | Public TikTok handle, e.g. &#39;jennmelon&#39; |  |

### Return type

[**TiktokUsersResolveGet200Response**](TiktokUsersResolveGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## tiktok_videos_batch_post

> <TiktokFeedRecommendedPost200Response> tiktok_videos_batch_post(opts)

Batch-fetch TikTok videos by ID

Returns canonicalized metadata for up to 20 TikTok videos.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::TiktokApi.new
opts = {
  tiktok_videos_batch_post_request: Unifapi::TiktokVideosBatchPostRequest.new({ids: ['ids_example']}) # TiktokVideosBatchPostRequest | 
}

begin
  # Batch-fetch TikTok videos by ID
  result = api_instance.tiktok_videos_batch_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_videos_batch_post: #{e}"
end
```

#### Using the tiktok_videos_batch_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<TiktokFeedRecommendedPost200Response>, Integer, Hash)> tiktok_videos_batch_post_with_http_info(opts)

```ruby
begin
  # Batch-fetch TikTok videos by ID
  data, status_code, headers = api_instance.tiktok_videos_batch_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <TiktokFeedRecommendedPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_videos_batch_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **tiktok_videos_batch_post_request** | [**TiktokVideosBatchPostRequest**](TiktokVideosBatchPostRequest.md) |  | [optional] |

### Return type

[**TiktokFeedRecommendedPost200Response**](TiktokFeedRecommendedPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## tiktok_videos_id_comments_comment_id_replies_get

> <TiktokVideosIdCommentsCommentIdRepliesGet200Response> tiktok_videos_id_comments_comment_id_replies_get(id, comment_id, opts)

List replies to a TikTok comment

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::TiktokApi.new
id = 'id_example' # String | 
comment_id = 'comment_id_example' # String | 
opts = {
  cursor: 'cursor_example', # String | 
  limit: 56 # Integer | 
}

begin
  # List replies to a TikTok comment
  result = api_instance.tiktok_videos_id_comments_comment_id_replies_get(id, comment_id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_videos_id_comments_comment_id_replies_get: #{e}"
end
```

#### Using the tiktok_videos_id_comments_comment_id_replies_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<TiktokVideosIdCommentsCommentIdRepliesGet200Response>, Integer, Hash)> tiktok_videos_id_comments_comment_id_replies_get_with_http_info(id, comment_id, opts)

```ruby
begin
  # List replies to a TikTok comment
  data, status_code, headers = api_instance.tiktok_videos_id_comments_comment_id_replies_get_with_http_info(id, comment_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <TiktokVideosIdCommentsCommentIdRepliesGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_videos_id_comments_comment_id_replies_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **comment_id** | **String** |  |  |
| **cursor** | **String** |  | [optional] |
| **limit** | **Integer** |  | [optional][default to 20] |

### Return type

[**TiktokVideosIdCommentsCommentIdRepliesGet200Response**](TiktokVideosIdCommentsCommentIdRepliesGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## tiktok_videos_id_comments_get

> <TiktokVideosIdCommentsCommentIdRepliesGet200Response> tiktok_videos_id_comments_get(id, opts)

List top-level comments on a TikTok video

Returns a paginated list of top-level comments on the given video. Use `next_cursor` from the response as the next request's `cursor`.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::TiktokApi.new
id = 'id_example' # String | 
opts = {
  cursor: 'cursor_example', # String | 
  limit: 56 # Integer | 
}

begin
  # List top-level comments on a TikTok video
  result = api_instance.tiktok_videos_id_comments_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_videos_id_comments_get: #{e}"
end
```

#### Using the tiktok_videos_id_comments_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<TiktokVideosIdCommentsCommentIdRepliesGet200Response>, Integer, Hash)> tiktok_videos_id_comments_get_with_http_info(id, opts)

```ruby
begin
  # List top-level comments on a TikTok video
  data, status_code, headers = api_instance.tiktok_videos_id_comments_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <TiktokVideosIdCommentsCommentIdRepliesGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_videos_id_comments_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **cursor** | **String** |  | [optional] |
| **limit** | **Integer** |  | [optional][default to 20] |

### Return type

[**TiktokVideosIdCommentsCommentIdRepliesGet200Response**](TiktokVideosIdCommentsCommentIdRepliesGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## tiktok_videos_id_get

> <TiktokVideosIdGet200Response> tiktok_videos_id_get(id)

Get a TikTok video by ID

Returns canonicalized metadata for a single TikTok video. The `{id}` must be the numeric TikTok video id.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::TiktokApi.new
id = 'id_example' # String | 

begin
  # Get a TikTok video by ID
  result = api_instance.tiktok_videos_id_get(id)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_videos_id_get: #{e}"
end
```

#### Using the tiktok_videos_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<TiktokVideosIdGet200Response>, Integer, Hash)> tiktok_videos_id_get_with_http_info(id)

```ruby
begin
  # Get a TikTok video by ID
  data, status_code, headers = api_instance.tiktok_videos_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <TiktokVideosIdGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_videos_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**TiktokVideosIdGet200Response**](TiktokVideosIdGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## tiktok_videos_resolve_get

> <TiktokVideosIdGet200Response> tiktok_videos_resolve_get(url)

Resolve a TikTok share URL to a video

Accepts a TikTok share URL (long or short / vm.tiktok.com) and returns the canonical Video object.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::TiktokApi.new
url = 'url_example' # String | TikTok share URL (long or short form)

begin
  # Resolve a TikTok share URL to a video
  result = api_instance.tiktok_videos_resolve_get(url)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_videos_resolve_get: #{e}"
end
```

#### Using the tiktok_videos_resolve_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<TiktokVideosIdGet200Response>, Integer, Hash)> tiktok_videos_resolve_get_with_http_info(url)

```ruby
begin
  # Resolve a TikTok share URL to a video
  data, status_code, headers = api_instance.tiktok_videos_resolve_get_with_http_info(url)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <TiktokVideosIdGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling TiktokApi->tiktok_videos_resolve_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **url** | **String** | TikTok share URL (long or short form) |  |

### Return type

[**TiktokVideosIdGet200Response**](TiktokVideosIdGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

