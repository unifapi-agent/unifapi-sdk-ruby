# Unifapi::InstagramApi

All URIs are relative to *https://api.unifapi.com*

| Method | HTTP request | Description |
| ------ | ------------ | ----------- |
| [**instagram_explore_get**](InstagramApi.md#instagram_explore_get) | **GET** /instagram/explore | Browse Instagram&#39;s Explore feed |
| [**instagram_locations_id_get**](InstagramApi.md#instagram_locations_id_get) | **GET** /instagram/locations/{id} | Get an Instagram location by id |
| [**instagram_locations_id_nearby_get**](InstagramApi.md#instagram_locations_id_nearby_get) | **GET** /instagram/locations/{id}/nearby | List Instagram locations geographically near a given location |
| [**instagram_locations_id_posts_get**](InstagramApi.md#instagram_locations_id_posts_get) | **GET** /instagram/locations/{id}/posts | List posts tagged with an Instagram location |
| [**instagram_posts_shortcode_comments_comment_id_replies_get**](InstagramApi.md#instagram_posts_shortcode_comments_comment_id_replies_get) | **GET** /instagram/posts/{shortcode}/comments/{commentId}/replies | List replies to an Instagram comment |
| [**instagram_posts_shortcode_comments_get**](InstagramApi.md#instagram_posts_shortcode_comments_get) | **GET** /instagram/posts/{shortcode}/comments | List comments on an Instagram post |
| [**instagram_posts_shortcode_get**](InstagramApi.md#instagram_posts_shortcode_get) | **GET** /instagram/posts/{shortcode} | Get an Instagram post (photo / video / carousel / reel) by shortcode |
| [**instagram_reels_recommended_get**](InstagramApi.md#instagram_reels_recommended_get) | **GET** /instagram/reels/recommended | Browse Instagram&#39;s recommended Reels feed |
| [**instagram_resolve_media_id_get**](InstagramApi.md#instagram_resolve_media_id_get) | **GET** /instagram/resolve/media-id | Convert an Instagram post shortcode into its numeric media_id |
| [**instagram_resolve_shortcode_from_media_get**](InstagramApi.md#instagram_resolve_shortcode_from_media_get) | **GET** /instagram/resolve/shortcode-from-media | Convert an Instagram numeric media_id into its shortcode |
| [**instagram_resolve_shortcode_get**](InstagramApi.md#instagram_resolve_shortcode_get) | **GET** /instagram/resolve/shortcode | Extract a post shortcode from an Instagram URL |
| [**instagram_resolve_user_id_get**](InstagramApi.md#instagram_resolve_user_id_get) | **GET** /instagram/resolve/user-id | Convert an Instagram username into its numeric user_id (pk) |
| [**instagram_search_get**](InstagramApi.md#instagram_search_get) | **GET** /instagram/search | Cross-type Instagram search (posts/reels) |
| [**instagram_users_username_followers_get**](InstagramApi.md#instagram_users_username_followers_get) | **GET** /instagram/users/{username}/followers | List followers of an Instagram user |
| [**instagram_users_username_following_get**](InstagramApi.md#instagram_users_username_following_get) | **GET** /instagram/users/{username}/following | List accounts an Instagram user follows |
| [**instagram_users_username_former_usernames_get**](InstagramApi.md#instagram_users_username_former_usernames_get) | **GET** /instagram/users/{username}/former-usernames | List former usernames for an Instagram user |
| [**instagram_users_username_get**](InstagramApi.md#instagram_users_username_get) | **GET** /instagram/users/{username} | Get an Instagram user profile by username |
| [**instagram_users_username_highlights_get**](InstagramApi.md#instagram_users_username_highlights_get) | **GET** /instagram/users/{username}/highlights | List Instagram highlight reels for a user (metadata only) |
| [**instagram_users_username_posts_get**](InstagramApi.md#instagram_users_username_posts_get) | **GET** /instagram/users/{username}/posts | List feed posts authored by an Instagram user |
| [**instagram_users_username_reels_get**](InstagramApi.md#instagram_users_username_reels_get) | **GET** /instagram/users/{username}/reels | List reels authored by an Instagram user |
| [**instagram_users_username_stories_get**](InstagramApi.md#instagram_users_username_stories_get) | **GET** /instagram/users/{username}/stories | List active Instagram stories for a user |
| [**instagram_users_username_tagged_posts_get**](InstagramApi.md#instagram_users_username_tagged_posts_get) | **GET** /instagram/users/{username}/tagged-posts | List posts an Instagram user is tagged in |


## instagram_explore_get

> <InstagramExploreGet200Response> instagram_explore_get(opts)

Browse Instagram's Explore feed

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::InstagramApi.new
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # Browse Instagram's Explore feed
  result = api_instance.instagram_explore_get(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_explore_get: #{e}"
end
```

#### Using the instagram_explore_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<InstagramExploreGet200Response>, Integer, Hash)> instagram_explore_get_with_http_info(opts)

```ruby
begin
  # Browse Instagram's Explore feed
  data, status_code, headers = api_instance.instagram_explore_get_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <InstagramExploreGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_explore_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **cursor** | **String** |  | [optional] |

### Return type

[**InstagramExploreGet200Response**](InstagramExploreGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## instagram_locations_id_get

> <InstagramLocationsIdGet200Response> instagram_locations_id_get(id)

Get an Instagram location by id

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::InstagramApi.new
id = 'id_example' # String | Numeric Instagram location id.

begin
  # Get an Instagram location by id
  result = api_instance.instagram_locations_id_get(id)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_locations_id_get: #{e}"
end
```

#### Using the instagram_locations_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<InstagramLocationsIdGet200Response>, Integer, Hash)> instagram_locations_id_get_with_http_info(id)

```ruby
begin
  # Get an Instagram location by id
  data, status_code, headers = api_instance.instagram_locations_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <InstagramLocationsIdGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_locations_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | Numeric Instagram location id. |  |

### Return type

[**InstagramLocationsIdGet200Response**](InstagramLocationsIdGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## instagram_locations_id_nearby_get

> <InstagramLocationsIdNearbyGet200Response> instagram_locations_id_nearby_get(id)

List Instagram locations geographically near a given location

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::InstagramApi.new
id = 'id_example' # String | 

begin
  # List Instagram locations geographically near a given location
  result = api_instance.instagram_locations_id_nearby_get(id)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_locations_id_nearby_get: #{e}"
end
```

#### Using the instagram_locations_id_nearby_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<InstagramLocationsIdNearbyGet200Response>, Integer, Hash)> instagram_locations_id_nearby_get_with_http_info(id)

```ruby
begin
  # List Instagram locations geographically near a given location
  data, status_code, headers = api_instance.instagram_locations_id_nearby_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <InstagramLocationsIdNearbyGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_locations_id_nearby_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**InstagramLocationsIdNearbyGet200Response**](InstagramLocationsIdNearbyGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## instagram_locations_id_posts_get

> <InstagramExploreGet200Response> instagram_locations_id_posts_get(id, opts)

List posts tagged with an Instagram location

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::InstagramApi.new
id = 'id_example' # String | 
opts = {
  cursor: 'cursor_example', # String | 
  tab: 'ranked' # String | Which tab to fetch — `ranked` (top) or `recent` (latest).
}

begin
  # List posts tagged with an Instagram location
  result = api_instance.instagram_locations_id_posts_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_locations_id_posts_get: #{e}"
end
```

#### Using the instagram_locations_id_posts_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<InstagramExploreGet200Response>, Integer, Hash)> instagram_locations_id_posts_get_with_http_info(id, opts)

```ruby
begin
  # List posts tagged with an Instagram location
  data, status_code, headers = api_instance.instagram_locations_id_posts_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <InstagramExploreGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_locations_id_posts_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **cursor** | **String** |  | [optional] |
| **tab** | **String** | Which tab to fetch — &#x60;ranked&#x60; (top) or &#x60;recent&#x60; (latest). | [optional] |

### Return type

[**InstagramExploreGet200Response**](InstagramExploreGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## instagram_posts_shortcode_comments_comment_id_replies_get

> <InstagramPostsShortcodeCommentsCommentIdRepliesGet200Response> instagram_posts_shortcode_comments_comment_id_replies_get(shortcode, comment_id, opts)

List replies to an Instagram comment

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::InstagramApi.new
shortcode = 'shortcode_example' # String | 
comment_id = 'comment_id_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List replies to an Instagram comment
  result = api_instance.instagram_posts_shortcode_comments_comment_id_replies_get(shortcode, comment_id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_posts_shortcode_comments_comment_id_replies_get: #{e}"
end
```

#### Using the instagram_posts_shortcode_comments_comment_id_replies_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<InstagramPostsShortcodeCommentsCommentIdRepliesGet200Response>, Integer, Hash)> instagram_posts_shortcode_comments_comment_id_replies_get_with_http_info(shortcode, comment_id, opts)

```ruby
begin
  # List replies to an Instagram comment
  data, status_code, headers = api_instance.instagram_posts_shortcode_comments_comment_id_replies_get_with_http_info(shortcode, comment_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <InstagramPostsShortcodeCommentsCommentIdRepliesGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_posts_shortcode_comments_comment_id_replies_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **shortcode** | **String** |  |  |
| **comment_id** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**InstagramPostsShortcodeCommentsCommentIdRepliesGet200Response**](InstagramPostsShortcodeCommentsCommentIdRepliesGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## instagram_posts_shortcode_comments_get

> <InstagramPostsShortcodeCommentsCommentIdRepliesGet200Response> instagram_posts_shortcode_comments_get(shortcode, opts)

List comments on an Instagram post

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::InstagramApi.new
shortcode = 'shortcode_example' # String | 
opts = {
  cursor: 'cursor_example', # String | 
  sort: 'popular' # String | 
}

begin
  # List comments on an Instagram post
  result = api_instance.instagram_posts_shortcode_comments_get(shortcode, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_posts_shortcode_comments_get: #{e}"
end
```

#### Using the instagram_posts_shortcode_comments_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<InstagramPostsShortcodeCommentsCommentIdRepliesGet200Response>, Integer, Hash)> instagram_posts_shortcode_comments_get_with_http_info(shortcode, opts)

```ruby
begin
  # List comments on an Instagram post
  data, status_code, headers = api_instance.instagram_posts_shortcode_comments_get_with_http_info(shortcode, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <InstagramPostsShortcodeCommentsCommentIdRepliesGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_posts_shortcode_comments_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **shortcode** | **String** |  |  |
| **cursor** | **String** |  | [optional] |
| **sort** | **String** |  | [optional] |

### Return type

[**InstagramPostsShortcodeCommentsCommentIdRepliesGet200Response**](InstagramPostsShortcodeCommentsCommentIdRepliesGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## instagram_posts_shortcode_get

> <InstagramPostsShortcodeGet200Response> instagram_posts_shortcode_get(shortcode)

Get an Instagram post (photo / video / carousel / reel) by shortcode

`shortcode` is the slug from the post URL, e.g. `DUajw4YkorV` in `instagram.com/p/DUajw4YkorV/`.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::InstagramApi.new
shortcode = 'shortcode_example' # String | 

begin
  # Get an Instagram post (photo / video / carousel / reel) by shortcode
  result = api_instance.instagram_posts_shortcode_get(shortcode)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_posts_shortcode_get: #{e}"
end
```

#### Using the instagram_posts_shortcode_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<InstagramPostsShortcodeGet200Response>, Integer, Hash)> instagram_posts_shortcode_get_with_http_info(shortcode)

```ruby
begin
  # Get an Instagram post (photo / video / carousel / reel) by shortcode
  data, status_code, headers = api_instance.instagram_posts_shortcode_get_with_http_info(shortcode)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <InstagramPostsShortcodeGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_posts_shortcode_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **shortcode** | **String** |  |  |

### Return type

[**InstagramPostsShortcodeGet200Response**](InstagramPostsShortcodeGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## instagram_reels_recommended_get

> <InstagramExploreGet200Response> instagram_reels_recommended_get(opts)

Browse Instagram's recommended Reels feed

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::InstagramApi.new
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # Browse Instagram's recommended Reels feed
  result = api_instance.instagram_reels_recommended_get(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_reels_recommended_get: #{e}"
end
```

#### Using the instagram_reels_recommended_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<InstagramExploreGet200Response>, Integer, Hash)> instagram_reels_recommended_get_with_http_info(opts)

```ruby
begin
  # Browse Instagram's recommended Reels feed
  data, status_code, headers = api_instance.instagram_reels_recommended_get_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <InstagramExploreGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_reels_recommended_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **cursor** | **String** |  | [optional] |

### Return type

[**InstagramExploreGet200Response**](InstagramExploreGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## instagram_resolve_media_id_get

> <InstagramResolveMediaIdGet200Response> instagram_resolve_media_id_get(shortcode)

Convert an Instagram post shortcode into its numeric media_id

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::InstagramApi.new
shortcode = 'shortcode_example' # String | 

begin
  # Convert an Instagram post shortcode into its numeric media_id
  result = api_instance.instagram_resolve_media_id_get(shortcode)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_resolve_media_id_get: #{e}"
end
```

#### Using the instagram_resolve_media_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<InstagramResolveMediaIdGet200Response>, Integer, Hash)> instagram_resolve_media_id_get_with_http_info(shortcode)

```ruby
begin
  # Convert an Instagram post shortcode into its numeric media_id
  data, status_code, headers = api_instance.instagram_resolve_media_id_get_with_http_info(shortcode)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <InstagramResolveMediaIdGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_resolve_media_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **shortcode** | **String** |  |  |

### Return type

[**InstagramResolveMediaIdGet200Response**](InstagramResolveMediaIdGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## instagram_resolve_shortcode_from_media_get

> <InstagramResolveMediaIdGet200Response> instagram_resolve_shortcode_from_media_get(media_id)

Convert an Instagram numeric media_id into its shortcode

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::InstagramApi.new
media_id = 'media_id_example' # String | 

begin
  # Convert an Instagram numeric media_id into its shortcode
  result = api_instance.instagram_resolve_shortcode_from_media_get(media_id)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_resolve_shortcode_from_media_get: #{e}"
end
```

#### Using the instagram_resolve_shortcode_from_media_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<InstagramResolveMediaIdGet200Response>, Integer, Hash)> instagram_resolve_shortcode_from_media_get_with_http_info(media_id)

```ruby
begin
  # Convert an Instagram numeric media_id into its shortcode
  data, status_code, headers = api_instance.instagram_resolve_shortcode_from_media_get_with_http_info(media_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <InstagramResolveMediaIdGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_resolve_shortcode_from_media_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **media_id** | **String** |  |  |

### Return type

[**InstagramResolveMediaIdGet200Response**](InstagramResolveMediaIdGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## instagram_resolve_shortcode_get

> <InstagramResolveShortcodeGet200Response> instagram_resolve_shortcode_get(url)

Extract a post shortcode from an Instagram URL

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::InstagramApi.new
url = 'url_example' # String | 

begin
  # Extract a post shortcode from an Instagram URL
  result = api_instance.instagram_resolve_shortcode_get(url)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_resolve_shortcode_get: #{e}"
end
```

#### Using the instagram_resolve_shortcode_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<InstagramResolveShortcodeGet200Response>, Integer, Hash)> instagram_resolve_shortcode_get_with_http_info(url)

```ruby
begin
  # Extract a post shortcode from an Instagram URL
  data, status_code, headers = api_instance.instagram_resolve_shortcode_get_with_http_info(url)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <InstagramResolveShortcodeGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_resolve_shortcode_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **url** | **String** |  |  |

### Return type

[**InstagramResolveShortcodeGet200Response**](InstagramResolveShortcodeGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## instagram_resolve_user_id_get

> <InstagramResolveUserIdGet200Response> instagram_resolve_user_id_get(username)

Convert an Instagram username into its numeric user_id (pk)

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::InstagramApi.new
username = 'username_example' # String | 

begin
  # Convert an Instagram username into its numeric user_id (pk)
  result = api_instance.instagram_resolve_user_id_get(username)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_resolve_user_id_get: #{e}"
end
```

#### Using the instagram_resolve_user_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<InstagramResolveUserIdGet200Response>, Integer, Hash)> instagram_resolve_user_id_get_with_http_info(username)

```ruby
begin
  # Convert an Instagram username into its numeric user_id (pk)
  data, status_code, headers = api_instance.instagram_resolve_user_id_get_with_http_info(username)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <InstagramResolveUserIdGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_resolve_user_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |

### Return type

[**InstagramResolveUserIdGet200Response**](InstagramResolveUserIdGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## instagram_search_get

> <InstagramExploreGet200Response> instagram_search_get(q, opts)

Cross-type Instagram search (posts/reels)

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::InstagramApi.new
q = 'q_example' # String | Search keyword.
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # Cross-type Instagram search (posts/reels)
  result = api_instance.instagram_search_get(q, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_search_get: #{e}"
end
```

#### Using the instagram_search_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<InstagramExploreGet200Response>, Integer, Hash)> instagram_search_get_with_http_info(q, opts)

```ruby
begin
  # Cross-type Instagram search (posts/reels)
  data, status_code, headers = api_instance.instagram_search_get_with_http_info(q, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <InstagramExploreGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_search_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **q** | **String** | Search keyword. |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**InstagramExploreGet200Response**](InstagramExploreGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## instagram_users_username_followers_get

> <InstagramUsersUsernameFollowersGet200Response> instagram_users_username_followers_get(username, opts)

List followers of an Instagram user

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::InstagramApi.new
username = 'username_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List followers of an Instagram user
  result = api_instance.instagram_users_username_followers_get(username, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_users_username_followers_get: #{e}"
end
```

#### Using the instagram_users_username_followers_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<InstagramUsersUsernameFollowersGet200Response>, Integer, Hash)> instagram_users_username_followers_get_with_http_info(username, opts)

```ruby
begin
  # List followers of an Instagram user
  data, status_code, headers = api_instance.instagram_users_username_followers_get_with_http_info(username, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <InstagramUsersUsernameFollowersGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_users_username_followers_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**InstagramUsersUsernameFollowersGet200Response**](InstagramUsersUsernameFollowersGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## instagram_users_username_following_get

> <InstagramUsersUsernameFollowersGet200Response> instagram_users_username_following_get(username, opts)

List accounts an Instagram user follows

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::InstagramApi.new
username = 'username_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List accounts an Instagram user follows
  result = api_instance.instagram_users_username_following_get(username, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_users_username_following_get: #{e}"
end
```

#### Using the instagram_users_username_following_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<InstagramUsersUsernameFollowersGet200Response>, Integer, Hash)> instagram_users_username_following_get_with_http_info(username, opts)

```ruby
begin
  # List accounts an Instagram user follows
  data, status_code, headers = api_instance.instagram_users_username_following_get_with_http_info(username, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <InstagramUsersUsernameFollowersGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_users_username_following_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**InstagramUsersUsernameFollowersGet200Response**](InstagramUsersUsernameFollowersGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## instagram_users_username_former_usernames_get

> <InstagramUsersUsernameFormerUsernamesGet200Response> instagram_users_username_former_usernames_get(username)

List former usernames for an Instagram user

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::InstagramApi.new
username = 'username_example' # String | 

begin
  # List former usernames for an Instagram user
  result = api_instance.instagram_users_username_former_usernames_get(username)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_users_username_former_usernames_get: #{e}"
end
```

#### Using the instagram_users_username_former_usernames_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<InstagramUsersUsernameFormerUsernamesGet200Response>, Integer, Hash)> instagram_users_username_former_usernames_get_with_http_info(username)

```ruby
begin
  # List former usernames for an Instagram user
  data, status_code, headers = api_instance.instagram_users_username_former_usernames_get_with_http_info(username)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <InstagramUsersUsernameFormerUsernamesGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_users_username_former_usernames_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |

### Return type

[**InstagramUsersUsernameFormerUsernamesGet200Response**](InstagramUsersUsernameFormerUsernamesGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## instagram_users_username_get

> <InstagramUsersUsernameGet200Response> instagram_users_username_get(username)

Get an Instagram user profile by username

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::InstagramApi.new
username = 'username_example' # String | Instagram URL slug, e.g. `instagram`

begin
  # Get an Instagram user profile by username
  result = api_instance.instagram_users_username_get(username)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_users_username_get: #{e}"
end
```

#### Using the instagram_users_username_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<InstagramUsersUsernameGet200Response>, Integer, Hash)> instagram_users_username_get_with_http_info(username)

```ruby
begin
  # Get an Instagram user profile by username
  data, status_code, headers = api_instance.instagram_users_username_get_with_http_info(username)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <InstagramUsersUsernameGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_users_username_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** | Instagram URL slug, e.g. &#x60;instagram&#x60; |  |

### Return type

[**InstagramUsersUsernameGet200Response**](InstagramUsersUsernameGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## instagram_users_username_highlights_get

> <InstagramUsersUsernameHighlightsGet200Response> instagram_users_username_highlights_get(username, opts)

List Instagram highlight reels for a user (metadata only)

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::InstagramApi.new
username = 'username_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List Instagram highlight reels for a user (metadata only)
  result = api_instance.instagram_users_username_highlights_get(username, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_users_username_highlights_get: #{e}"
end
```

#### Using the instagram_users_username_highlights_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<InstagramUsersUsernameHighlightsGet200Response>, Integer, Hash)> instagram_users_username_highlights_get_with_http_info(username, opts)

```ruby
begin
  # List Instagram highlight reels for a user (metadata only)
  data, status_code, headers = api_instance.instagram_users_username_highlights_get_with_http_info(username, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <InstagramUsersUsernameHighlightsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_users_username_highlights_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**InstagramUsersUsernameHighlightsGet200Response**](InstagramUsersUsernameHighlightsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## instagram_users_username_posts_get

> <InstagramExploreGet200Response> instagram_users_username_posts_get(username, opts)

List feed posts authored by an Instagram user

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::InstagramApi.new
username = 'username_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List feed posts authored by an Instagram user
  result = api_instance.instagram_users_username_posts_get(username, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_users_username_posts_get: #{e}"
end
```

#### Using the instagram_users_username_posts_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<InstagramExploreGet200Response>, Integer, Hash)> instagram_users_username_posts_get_with_http_info(username, opts)

```ruby
begin
  # List feed posts authored by an Instagram user
  data, status_code, headers = api_instance.instagram_users_username_posts_get_with_http_info(username, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <InstagramExploreGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_users_username_posts_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**InstagramExploreGet200Response**](InstagramExploreGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## instagram_users_username_reels_get

> <InstagramExploreGet200Response> instagram_users_username_reels_get(username, opts)

List reels authored by an Instagram user

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::InstagramApi.new
username = 'username_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List reels authored by an Instagram user
  result = api_instance.instagram_users_username_reels_get(username, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_users_username_reels_get: #{e}"
end
```

#### Using the instagram_users_username_reels_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<InstagramExploreGet200Response>, Integer, Hash)> instagram_users_username_reels_get_with_http_info(username, opts)

```ruby
begin
  # List reels authored by an Instagram user
  data, status_code, headers = api_instance.instagram_users_username_reels_get_with_http_info(username, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <InstagramExploreGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_users_username_reels_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**InstagramExploreGet200Response**](InstagramExploreGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## instagram_users_username_stories_get

> <InstagramExploreGet200Response> instagram_users_username_stories_get(username)

List active Instagram stories for a user

Returns the user's currently-live story tray (empty when the user has no active stories).

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::InstagramApi.new
username = 'username_example' # String | 

begin
  # List active Instagram stories for a user
  result = api_instance.instagram_users_username_stories_get(username)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_users_username_stories_get: #{e}"
end
```

#### Using the instagram_users_username_stories_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<InstagramExploreGet200Response>, Integer, Hash)> instagram_users_username_stories_get_with_http_info(username)

```ruby
begin
  # List active Instagram stories for a user
  data, status_code, headers = api_instance.instagram_users_username_stories_get_with_http_info(username)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <InstagramExploreGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_users_username_stories_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |

### Return type

[**InstagramExploreGet200Response**](InstagramExploreGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## instagram_users_username_tagged_posts_get

> <InstagramExploreGet200Response> instagram_users_username_tagged_posts_get(username, opts)

List posts an Instagram user is tagged in

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::InstagramApi.new
username = 'username_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List posts an Instagram user is tagged in
  result = api_instance.instagram_users_username_tagged_posts_get(username, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_users_username_tagged_posts_get: #{e}"
end
```

#### Using the instagram_users_username_tagged_posts_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<InstagramExploreGet200Response>, Integer, Hash)> instagram_users_username_tagged_posts_get_with_http_info(username, opts)

```ruby
begin
  # List posts an Instagram user is tagged in
  data, status_code, headers = api_instance.instagram_users_username_tagged_posts_get_with_http_info(username, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <InstagramExploreGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling InstagramApi->instagram_users_username_tagged_posts_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**InstagramExploreGet200Response**](InstagramExploreGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

