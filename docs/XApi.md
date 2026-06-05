# Unifapi::XApi

All URIs are relative to *https://api.unifapi.com*

| Method | HTTP request | Description |
| ------ | ------------ | ----------- |
| [**x_autocomplete_get**](XApi.md#x_autocomplete_get) | **GET** /x/autocomplete | Autocomplete X users, topics, hashtags, and cashtags |
| [**x_communities_id_about_get**](XApi.md#x_communities_id_about_get) | **GET** /x/communities/{id}/about | Get an X Community about timeline |
| [**x_communities_id_get**](XApi.md#x_communities_id_get) | **GET** /x/communities/{id} | Get X Community by ID |
| [**x_communities_id_media_get**](XApi.md#x_communities_id_media_get) | **GET** /x/communities/{id}/media | Get media Posts from an X Community |
| [**x_communities_id_member_search_get**](XApi.md#x_communities_id_member_search_get) | **GET** /x/communities/{id}/member_search | Search members in an X Community |
| [**x_communities_id_members_get**](XApi.md#x_communities_id_members_get) | **GET** /x/communities/{id}/members | Get members of an X Community |
| [**x_communities_id_moderators_get**](XApi.md#x_communities_id_moderators_get) | **GET** /x/communities/{id}/moderators | Get moderators of an X Community |
| [**x_communities_id_tweets_get**](XApi.md#x_communities_id_tweets_get) | **GET** /x/communities/{id}/tweets | Get Posts from an X Community |
| [**x_communities_search_get**](XApi.md#x_communities_search_get) | **GET** /x/communities/search | Search X Communities |
| [**x_friendships_show_get**](XApi.md#x_friendships_show_get) | **GET** /x/friendships/show | Check whether one X user follows another |
| [**x_lists_id_followers_get**](XApi.md#x_lists_id_followers_get) | **GET** /x/lists/{id}/followers | Get followers/subscribers of an X List |
| [**x_lists_id_members_get**](XApi.md#x_lists_id_members_get) | **GET** /x/lists/{id}/members | Get members of an X List |
| [**x_lists_id_tweets_get**](XApi.md#x_lists_id_tweets_get) | **GET** /x/lists/{id}/tweets | Get Posts from an X List |
| [**x_lists_search_get**](XApi.md#x_lists_search_get) | **GET** /x/lists/search | Search X Lists |
| [**x_trends_by_woeid_woeid_get**](XApi.md#x_trends_by_woeid_woeid_get) | **GET** /x/trends/by/woeid/{woeid} | Get X trends by WOEID |
| [**x_tweets_get**](XApi.md#x_tweets_get) | **GET** /x/tweets | Get X Posts by IDs |
| [**x_tweets_id_article_get**](XApi.md#x_tweets_id_article_get) | **GET** /x/tweets/{id}/article | Get the article-style payload for an X Post |
| [**x_tweets_id_get**](XApi.md#x_tweets_id_get) | **GET** /x/tweets/{id} | Get X Post by ID |
| [**x_tweets_id_liking_users_get**](XApi.md#x_tweets_id_liking_users_get) | **GET** /x/tweets/{id}/liking_users | Get users who liked an X Post |
| [**x_tweets_id_quote_tweets_get**](XApi.md#x_tweets_id_quote_tweets_get) | **GET** /x/tweets/{id}/quote_tweets | Get quote Posts for an X Post |
| [**x_tweets_id_retweeted_by_get**](XApi.md#x_tweets_id_retweeted_by_get) | **GET** /x/tweets/{id}/retweeted_by | Get users who reposted an X Post |
| [**x_tweets_id_translation_get**](XApi.md#x_tweets_id_translation_get) | **GET** /x/tweets/{id}/translation | Translate an X Post |
| [**x_tweets_search_recent_get**](XApi.md#x_tweets_search_recent_get) | **GET** /x/tweets/search/recent | Search recent X Posts |
| [**x_users_by_get**](XApi.md#x_users_by_get) | **GET** /x/users/by | Get X users by usernames |
| [**x_users_by_username_username_get**](XApi.md#x_users_by_username_username_get) | **GET** /x/users/by/username/{username} | Get X user by username |
| [**x_users_get**](XApi.md#x_users_get) | **GET** /x/users | Get X users by IDs |
| [**x_users_id_followers_get**](XApi.md#x_users_id_followers_get) | **GET** /x/users/{id}/followers | Get an X user&#39;s followers |
| [**x_users_id_followers_ids_get**](XApi.md#x_users_id_followers_ids_get) | **GET** /x/users/{id}/followers/ids | Get follower IDs for an X user |
| [**x_users_id_following_get**](XApi.md#x_users_id_following_get) | **GET** /x/users/{id}/following | Get users followed by an X user |
| [**x_users_id_following_ids_get**](XApi.md#x_users_id_following_ids_get) | **GET** /x/users/{id}/following/ids | Get following IDs for an X user |
| [**x_users_id_get**](XApi.md#x_users_id_get) | **GET** /x/users/{id} | Get X user by ID |
| [**x_users_id_liked_tweets_get**](XApi.md#x_users_id_liked_tweets_get) | **GET** /x/users/{id}/liked_tweets | Get Posts liked by an X user |
| [**x_users_id_profile_translation_get**](XApi.md#x_users_id_profile_translation_get) | **GET** /x/users/{id}/profile_translation | Translate an X user profile |
| [**x_users_id_tweets_get**](XApi.md#x_users_id_tweets_get) | **GET** /x/users/{id}/tweets | Get Posts authored by an X user |
| [**x_users_id_verified_followers_get**](XApi.md#x_users_id_verified_followers_get) | **GET** /x/users/{id}/verified_followers | Get verified followers for an X user |


## x_autocomplete_get

> <XAutocompleteGet200Response> x_autocomplete_get(query)

Autocomplete X users, topics, hashtags, and cashtags

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
query = 'query_example' # String | 

begin
  # Autocomplete X users, topics, hashtags, and cashtags
  result = api_instance.x_autocomplete_get(query)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_autocomplete_get: #{e}"
end
```

#### Using the x_autocomplete_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XAutocompleteGet200Response>, Integer, Hash)> x_autocomplete_get_with_http_info(query)

```ruby
begin
  # Autocomplete X users, topics, hashtags, and cashtags
  data, status_code, headers = api_instance.x_autocomplete_get_with_http_info(query)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XAutocompleteGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_autocomplete_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **query** | **String** |  |  |

### Return type

[**XAutocompleteGet200Response**](XAutocompleteGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_communities_id_about_get

> <XCommunitiesIdAboutGet200Response> x_communities_id_about_get(id, opts)

Get an X Community about timeline

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
id = 'id_example' # String | X resource id.
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example', # String | 
  pagination_token: 'pagination_token_example', # String | 
  next_token: 'next_token_example', # String | 
  max_results: 56 # Integer | 
}

begin
  # Get an X Community about timeline
  result = api_instance.x_communities_id_about_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_communities_id_about_get: #{e}"
end
```

#### Using the x_communities_id_about_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XCommunitiesIdAboutGet200Response>, Integer, Hash)> x_communities_id_about_get_with_http_info(id, opts)

```ruby
begin
  # Get an X Community about timeline
  data, status_code, headers = api_instance.x_communities_id_about_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XCommunitiesIdAboutGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_communities_id_about_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | X resource id. |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |
| **pagination_token** | **String** |  | [optional] |
| **next_token** | **String** |  | [optional] |
| **max_results** | **Integer** |  | [optional] |

### Return type

[**XCommunitiesIdAboutGet200Response**](XCommunitiesIdAboutGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_communities_id_get

> <XCommunitiesIdGet200Response> x_communities_id_get(id, opts)

Get X Community by ID

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
id = 'id_example' # String | X resource id.
opts = {
  community_fields: 'community_fields_example' # String | 
}

begin
  # Get X Community by ID
  result = api_instance.x_communities_id_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_communities_id_get: #{e}"
end
```

#### Using the x_communities_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XCommunitiesIdGet200Response>, Integer, Hash)> x_communities_id_get_with_http_info(id, opts)

```ruby
begin
  # Get X Community by ID
  data, status_code, headers = api_instance.x_communities_id_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XCommunitiesIdGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_communities_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | X resource id. |  |
| **community_fields** | **String** |  | [optional] |

### Return type

[**XCommunitiesIdGet200Response**](XCommunitiesIdGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_communities_id_media_get

> <XCommunitiesIdAboutGet200Response> x_communities_id_media_get(id, opts)

Get media Posts from an X Community

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
id = 'id_example' # String | X resource id.
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example', # String | 
  pagination_token: 'pagination_token_example', # String | 
  next_token: 'next_token_example', # String | 
  max_results: 56 # Integer | 
}

begin
  # Get media Posts from an X Community
  result = api_instance.x_communities_id_media_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_communities_id_media_get: #{e}"
end
```

#### Using the x_communities_id_media_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XCommunitiesIdAboutGet200Response>, Integer, Hash)> x_communities_id_media_get_with_http_info(id, opts)

```ruby
begin
  # Get media Posts from an X Community
  data, status_code, headers = api_instance.x_communities_id_media_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XCommunitiesIdAboutGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_communities_id_media_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | X resource id. |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |
| **pagination_token** | **String** |  | [optional] |
| **next_token** | **String** |  | [optional] |
| **max_results** | **Integer** |  | [optional] |

### Return type

[**XCommunitiesIdAboutGet200Response**](XCommunitiesIdAboutGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_communities_id_member_search_get

> <XCommunitiesIdMemberSearchGet200Response> x_communities_id_member_search_get(id, query, opts)

Search members in an X Community

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
id = 'id_example' # String | X resource id.
query = 'query_example' # String | 
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example', # String | 
  pagination_token: 'pagination_token_example', # String | 
  next_token: 'next_token_example', # String | 
  max_results: 56 # Integer | 
}

begin
  # Search members in an X Community
  result = api_instance.x_communities_id_member_search_get(id, query, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_communities_id_member_search_get: #{e}"
end
```

#### Using the x_communities_id_member_search_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XCommunitiesIdMemberSearchGet200Response>, Integer, Hash)> x_communities_id_member_search_get_with_http_info(id, query, opts)

```ruby
begin
  # Search members in an X Community
  data, status_code, headers = api_instance.x_communities_id_member_search_get_with_http_info(id, query, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XCommunitiesIdMemberSearchGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_communities_id_member_search_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | X resource id. |  |
| **query** | **String** |  |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |
| **pagination_token** | **String** |  | [optional] |
| **next_token** | **String** |  | [optional] |
| **max_results** | **Integer** |  | [optional] |

### Return type

[**XCommunitiesIdMemberSearchGet200Response**](XCommunitiesIdMemberSearchGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_communities_id_members_get

> <XCommunitiesIdMemberSearchGet200Response> x_communities_id_members_get(id, opts)

Get members of an X Community

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
id = 'id_example' # String | X resource id.
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example', # String | 
  pagination_token: 'pagination_token_example', # String | 
  next_token: 'next_token_example', # String | 
  max_results: 56 # Integer | 
}

begin
  # Get members of an X Community
  result = api_instance.x_communities_id_members_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_communities_id_members_get: #{e}"
end
```

#### Using the x_communities_id_members_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XCommunitiesIdMemberSearchGet200Response>, Integer, Hash)> x_communities_id_members_get_with_http_info(id, opts)

```ruby
begin
  # Get members of an X Community
  data, status_code, headers = api_instance.x_communities_id_members_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XCommunitiesIdMemberSearchGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_communities_id_members_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | X resource id. |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |
| **pagination_token** | **String** |  | [optional] |
| **next_token** | **String** |  | [optional] |
| **max_results** | **Integer** |  | [optional] |

### Return type

[**XCommunitiesIdMemberSearchGet200Response**](XCommunitiesIdMemberSearchGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_communities_id_moderators_get

> <XCommunitiesIdMemberSearchGet200Response> x_communities_id_moderators_get(id, opts)

Get moderators of an X Community

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
id = 'id_example' # String | X resource id.
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example', # String | 
  pagination_token: 'pagination_token_example', # String | 
  next_token: 'next_token_example', # String | 
  max_results: 56 # Integer | 
}

begin
  # Get moderators of an X Community
  result = api_instance.x_communities_id_moderators_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_communities_id_moderators_get: #{e}"
end
```

#### Using the x_communities_id_moderators_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XCommunitiesIdMemberSearchGet200Response>, Integer, Hash)> x_communities_id_moderators_get_with_http_info(id, opts)

```ruby
begin
  # Get moderators of an X Community
  data, status_code, headers = api_instance.x_communities_id_moderators_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XCommunitiesIdMemberSearchGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_communities_id_moderators_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | X resource id. |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |
| **pagination_token** | **String** |  | [optional] |
| **next_token** | **String** |  | [optional] |
| **max_results** | **Integer** |  | [optional] |

### Return type

[**XCommunitiesIdMemberSearchGet200Response**](XCommunitiesIdMemberSearchGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_communities_id_tweets_get

> <XCommunitiesIdAboutGet200Response> x_communities_id_tweets_get(id, opts)

Get Posts from an X Community

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
id = 'id_example' # String | X resource id.
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example', # String | 
  pagination_token: 'pagination_token_example', # String | 
  next_token: 'next_token_example', # String | 
  max_results: 56 # Integer | 
}

begin
  # Get Posts from an X Community
  result = api_instance.x_communities_id_tweets_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_communities_id_tweets_get: #{e}"
end
```

#### Using the x_communities_id_tweets_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XCommunitiesIdAboutGet200Response>, Integer, Hash)> x_communities_id_tweets_get_with_http_info(id, opts)

```ruby
begin
  # Get Posts from an X Community
  data, status_code, headers = api_instance.x_communities_id_tweets_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XCommunitiesIdAboutGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_communities_id_tweets_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | X resource id. |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |
| **pagination_token** | **String** |  | [optional] |
| **next_token** | **String** |  | [optional] |
| **max_results** | **Integer** |  | [optional] |

### Return type

[**XCommunitiesIdAboutGet200Response**](XCommunitiesIdAboutGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_communities_search_get

> <XCommunitiesSearchGet200Response> x_communities_search_get(query, opts)

Search X Communities

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
query = 'query_example' # String | 
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example', # String | 
  pagination_token: 'pagination_token_example', # String | 
  next_token: 'next_token_example', # String | 
  max_results: 56, # Integer | 
  community_fields: 'community_fields_example' # String | 
}

begin
  # Search X Communities
  result = api_instance.x_communities_search_get(query, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_communities_search_get: #{e}"
end
```

#### Using the x_communities_search_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XCommunitiesSearchGet200Response>, Integer, Hash)> x_communities_search_get_with_http_info(query, opts)

```ruby
begin
  # Search X Communities
  data, status_code, headers = api_instance.x_communities_search_get_with_http_info(query, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XCommunitiesSearchGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_communities_search_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **query** | **String** |  |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |
| **pagination_token** | **String** |  | [optional] |
| **next_token** | **String** |  | [optional] |
| **max_results** | **Integer** |  | [optional] |
| **community_fields** | **String** |  | [optional] |

### Return type

[**XCommunitiesSearchGet200Response**](XCommunitiesSearchGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_friendships_show_get

> <XFriendshipsShowGet200Response> x_friendships_show_get(opts)

Check whether one X user follows another

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
opts = {
  source_id: 'source_id_example', # String | 
  target_id: 'target_id_example', # String | 
  source_screen_name: 'source_screen_name_example', # String | 
  target_screen_name: 'target_screen_name_example' # String | 
}

begin
  # Check whether one X user follows another
  result = api_instance.x_friendships_show_get(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_friendships_show_get: #{e}"
end
```

#### Using the x_friendships_show_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XFriendshipsShowGet200Response>, Integer, Hash)> x_friendships_show_get_with_http_info(opts)

```ruby
begin
  # Check whether one X user follows another
  data, status_code, headers = api_instance.x_friendships_show_get_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XFriendshipsShowGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_friendships_show_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **source_id** | **String** |  | [optional] |
| **target_id** | **String** |  | [optional] |
| **source_screen_name** | **String** |  | [optional] |
| **target_screen_name** | **String** |  | [optional] |

### Return type

[**XFriendshipsShowGet200Response**](XFriendshipsShowGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_lists_id_followers_get

> <XCommunitiesIdMemberSearchGet200Response> x_lists_id_followers_get(id, opts)

Get followers/subscribers of an X List

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
id = 'id_example' # String | X resource id.
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example', # String | 
  pagination_token: 'pagination_token_example', # String | 
  next_token: 'next_token_example', # String | 
  max_results: 56 # Integer | 
}

begin
  # Get followers/subscribers of an X List
  result = api_instance.x_lists_id_followers_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_lists_id_followers_get: #{e}"
end
```

#### Using the x_lists_id_followers_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XCommunitiesIdMemberSearchGet200Response>, Integer, Hash)> x_lists_id_followers_get_with_http_info(id, opts)

```ruby
begin
  # Get followers/subscribers of an X List
  data, status_code, headers = api_instance.x_lists_id_followers_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XCommunitiesIdMemberSearchGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_lists_id_followers_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | X resource id. |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |
| **pagination_token** | **String** |  | [optional] |
| **next_token** | **String** |  | [optional] |
| **max_results** | **Integer** |  | [optional] |

### Return type

[**XCommunitiesIdMemberSearchGet200Response**](XCommunitiesIdMemberSearchGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_lists_id_members_get

> <XCommunitiesIdMemberSearchGet200Response> x_lists_id_members_get(id, opts)

Get members of an X List

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
id = 'id_example' # String | X resource id.
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example', # String | 
  pagination_token: 'pagination_token_example', # String | 
  next_token: 'next_token_example', # String | 
  max_results: 56 # Integer | 
}

begin
  # Get members of an X List
  result = api_instance.x_lists_id_members_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_lists_id_members_get: #{e}"
end
```

#### Using the x_lists_id_members_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XCommunitiesIdMemberSearchGet200Response>, Integer, Hash)> x_lists_id_members_get_with_http_info(id, opts)

```ruby
begin
  # Get members of an X List
  data, status_code, headers = api_instance.x_lists_id_members_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XCommunitiesIdMemberSearchGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_lists_id_members_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | X resource id. |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |
| **pagination_token** | **String** |  | [optional] |
| **next_token** | **String** |  | [optional] |
| **max_results** | **Integer** |  | [optional] |

### Return type

[**XCommunitiesIdMemberSearchGet200Response**](XCommunitiesIdMemberSearchGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_lists_id_tweets_get

> <XCommunitiesIdAboutGet200Response> x_lists_id_tweets_get(id, opts)

Get Posts from an X List

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
id = 'id_example' # String | X resource id.
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example', # String | 
  pagination_token: 'pagination_token_example', # String | 
  next_token: 'next_token_example', # String | 
  max_results: 56 # Integer | 
}

begin
  # Get Posts from an X List
  result = api_instance.x_lists_id_tweets_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_lists_id_tweets_get: #{e}"
end
```

#### Using the x_lists_id_tweets_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XCommunitiesIdAboutGet200Response>, Integer, Hash)> x_lists_id_tweets_get_with_http_info(id, opts)

```ruby
begin
  # Get Posts from an X List
  data, status_code, headers = api_instance.x_lists_id_tweets_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XCommunitiesIdAboutGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_lists_id_tweets_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | X resource id. |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |
| **pagination_token** | **String** |  | [optional] |
| **next_token** | **String** |  | [optional] |
| **max_results** | **Integer** |  | [optional] |

### Return type

[**XCommunitiesIdAboutGet200Response**](XCommunitiesIdAboutGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_lists_search_get

> <XListsSearchGet200Response> x_lists_search_get(query, opts)

Search X Lists

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
query = 'query_example' # String | 
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example', # String | 
  pagination_token: 'pagination_token_example', # String | 
  next_token: 'next_token_example', # String | 
  max_results: 56 # Integer | 
}

begin
  # Search X Lists
  result = api_instance.x_lists_search_get(query, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_lists_search_get: #{e}"
end
```

#### Using the x_lists_search_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XListsSearchGet200Response>, Integer, Hash)> x_lists_search_get_with_http_info(query, opts)

```ruby
begin
  # Search X Lists
  data, status_code, headers = api_instance.x_lists_search_get_with_http_info(query, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XListsSearchGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_lists_search_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **query** | **String** |  |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |
| **pagination_token** | **String** |  | [optional] |
| **next_token** | **String** |  | [optional] |
| **max_results** | **Integer** |  | [optional] |

### Return type

[**XListsSearchGet200Response**](XListsSearchGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_trends_by_woeid_woeid_get

> <XTrendsByWoeidWoeidGet200Response> x_trends_by_woeid_woeid_get(woeid, opts)

Get X trends by WOEID

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
woeid = 'woeid_example' # String | 
opts = {
  max_trends: 56, # Integer | 
  trend_fields: 'trend_fields_example' # String | 
}

begin
  # Get X trends by WOEID
  result = api_instance.x_trends_by_woeid_woeid_get(woeid, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_trends_by_woeid_woeid_get: #{e}"
end
```

#### Using the x_trends_by_woeid_woeid_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XTrendsByWoeidWoeidGet200Response>, Integer, Hash)> x_trends_by_woeid_woeid_get_with_http_info(woeid, opts)

```ruby
begin
  # Get X trends by WOEID
  data, status_code, headers = api_instance.x_trends_by_woeid_woeid_get_with_http_info(woeid, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XTrendsByWoeidWoeidGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_trends_by_woeid_woeid_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **woeid** | **String** |  |  |
| **max_trends** | **Integer** |  | [optional] |
| **trend_fields** | **String** |  | [optional] |

### Return type

[**XTrendsByWoeidWoeidGet200Response**](XTrendsByWoeidWoeidGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_tweets_get

> <XTweetsGet200Response> x_tweets_get(ids, opts)

Get X Posts by IDs

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
ids = 'ids_example' # String | Comma-separated resource ids.
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example' # String | 
}

begin
  # Get X Posts by IDs
  result = api_instance.x_tweets_get(ids, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_tweets_get: #{e}"
end
```

#### Using the x_tweets_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XTweetsGet200Response>, Integer, Hash)> x_tweets_get_with_http_info(ids, opts)

```ruby
begin
  # Get X Posts by IDs
  data, status_code, headers = api_instance.x_tweets_get_with_http_info(ids, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XTweetsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_tweets_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **ids** | **String** | Comma-separated resource ids. |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |

### Return type

[**XTweetsGet200Response**](XTweetsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_tweets_id_article_get

> <XTweetsIdArticleGet200Response> x_tweets_id_article_get(id, opts)

Get the article-style payload for an X Post

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
id = 'id_example' # String | X resource id.
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example' # String | 
}

begin
  # Get the article-style payload for an X Post
  result = api_instance.x_tweets_id_article_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_tweets_id_article_get: #{e}"
end
```

#### Using the x_tweets_id_article_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XTweetsIdArticleGet200Response>, Integer, Hash)> x_tweets_id_article_get_with_http_info(id, opts)

```ruby
begin
  # Get the article-style payload for an X Post
  data, status_code, headers = api_instance.x_tweets_id_article_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XTweetsIdArticleGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_tweets_id_article_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | X resource id. |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |

### Return type

[**XTweetsIdArticleGet200Response**](XTweetsIdArticleGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_tweets_id_get

> <XTweetsIdGet200Response> x_tweets_id_get(id, opts)

Get X Post by ID

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
id = 'id_example' # String | X resource id.
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example' # String | 
}

begin
  # Get X Post by ID
  result = api_instance.x_tweets_id_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_tweets_id_get: #{e}"
end
```

#### Using the x_tweets_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XTweetsIdGet200Response>, Integer, Hash)> x_tweets_id_get_with_http_info(id, opts)

```ruby
begin
  # Get X Post by ID
  data, status_code, headers = api_instance.x_tweets_id_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XTweetsIdGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_tweets_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | X resource id. |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |

### Return type

[**XTweetsIdGet200Response**](XTweetsIdGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_tweets_id_liking_users_get

> <XCommunitiesIdMemberSearchGet200Response> x_tweets_id_liking_users_get(id, opts)

Get users who liked an X Post

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
id = 'id_example' # String | X resource id.
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example', # String | 
  pagination_token: 'pagination_token_example', # String | 
  next_token: 'next_token_example', # String | 
  max_results: 56 # Integer | 
}

begin
  # Get users who liked an X Post
  result = api_instance.x_tweets_id_liking_users_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_tweets_id_liking_users_get: #{e}"
end
```

#### Using the x_tweets_id_liking_users_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XCommunitiesIdMemberSearchGet200Response>, Integer, Hash)> x_tweets_id_liking_users_get_with_http_info(id, opts)

```ruby
begin
  # Get users who liked an X Post
  data, status_code, headers = api_instance.x_tweets_id_liking_users_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XCommunitiesIdMemberSearchGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_tweets_id_liking_users_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | X resource id. |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |
| **pagination_token** | **String** |  | [optional] |
| **next_token** | **String** |  | [optional] |
| **max_results** | **Integer** |  | [optional] |

### Return type

[**XCommunitiesIdMemberSearchGet200Response**](XCommunitiesIdMemberSearchGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_tweets_id_quote_tweets_get

> <XCommunitiesIdAboutGet200Response> x_tweets_id_quote_tweets_get(id, opts)

Get quote Posts for an X Post

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
id = 'id_example' # String | X resource id.
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example', # String | 
  pagination_token: 'pagination_token_example', # String | 
  next_token: 'next_token_example', # String | 
  max_results: 56 # Integer | 
}

begin
  # Get quote Posts for an X Post
  result = api_instance.x_tweets_id_quote_tweets_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_tweets_id_quote_tweets_get: #{e}"
end
```

#### Using the x_tweets_id_quote_tweets_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XCommunitiesIdAboutGet200Response>, Integer, Hash)> x_tweets_id_quote_tweets_get_with_http_info(id, opts)

```ruby
begin
  # Get quote Posts for an X Post
  data, status_code, headers = api_instance.x_tweets_id_quote_tweets_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XCommunitiesIdAboutGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_tweets_id_quote_tweets_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | X resource id. |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |
| **pagination_token** | **String** |  | [optional] |
| **next_token** | **String** |  | [optional] |
| **max_results** | **Integer** |  | [optional] |

### Return type

[**XCommunitiesIdAboutGet200Response**](XCommunitiesIdAboutGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_tweets_id_retweeted_by_get

> <XCommunitiesIdMemberSearchGet200Response> x_tweets_id_retweeted_by_get(id, opts)

Get users who reposted an X Post

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
id = 'id_example' # String | X resource id.
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example', # String | 
  pagination_token: 'pagination_token_example', # String | 
  next_token: 'next_token_example', # String | 
  max_results: 56 # Integer | 
}

begin
  # Get users who reposted an X Post
  result = api_instance.x_tweets_id_retweeted_by_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_tweets_id_retweeted_by_get: #{e}"
end
```

#### Using the x_tweets_id_retweeted_by_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XCommunitiesIdMemberSearchGet200Response>, Integer, Hash)> x_tweets_id_retweeted_by_get_with_http_info(id, opts)

```ruby
begin
  # Get users who reposted an X Post
  data, status_code, headers = api_instance.x_tweets_id_retweeted_by_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XCommunitiesIdMemberSearchGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_tweets_id_retweeted_by_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | X resource id. |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |
| **pagination_token** | **String** |  | [optional] |
| **next_token** | **String** |  | [optional] |
| **max_results** | **Integer** |  | [optional] |

### Return type

[**XCommunitiesIdMemberSearchGet200Response**](XCommunitiesIdMemberSearchGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_tweets_id_translation_get

> <XTweetsIdTranslationGet200Response> x_tweets_id_translation_get(id, language)

Translate an X Post

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
id = 'id_example' # String | X resource id.
language = 'language_example' # String | 

begin
  # Translate an X Post
  result = api_instance.x_tweets_id_translation_get(id, language)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_tweets_id_translation_get: #{e}"
end
```

#### Using the x_tweets_id_translation_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XTweetsIdTranslationGet200Response>, Integer, Hash)> x_tweets_id_translation_get_with_http_info(id, language)

```ruby
begin
  # Translate an X Post
  data, status_code, headers = api_instance.x_tweets_id_translation_get_with_http_info(id, language)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XTweetsIdTranslationGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_tweets_id_translation_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | X resource id. |  |
| **language** | **String** |  |  |

### Return type

[**XTweetsIdTranslationGet200Response**](XTweetsIdTranslationGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_tweets_search_recent_get

> <XCommunitiesIdAboutGet200Response> x_tweets_search_recent_get(query, opts)

Search recent X Posts

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
query = 'query_example' # String | Recent search query.
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example', # String | 
  pagination_token: 'pagination_token_example', # String | 
  next_token: 'next_token_example', # String | 
  max_results: 56 # Integer | 
}

begin
  # Search recent X Posts
  result = api_instance.x_tweets_search_recent_get(query, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_tweets_search_recent_get: #{e}"
end
```

#### Using the x_tweets_search_recent_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XCommunitiesIdAboutGet200Response>, Integer, Hash)> x_tweets_search_recent_get_with_http_info(query, opts)

```ruby
begin
  # Search recent X Posts
  data, status_code, headers = api_instance.x_tweets_search_recent_get_with_http_info(query, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XCommunitiesIdAboutGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_tweets_search_recent_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **query** | **String** | Recent search query. |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |
| **pagination_token** | **String** |  | [optional] |
| **next_token** | **String** |  | [optional] |
| **max_results** | **Integer** |  | [optional] |

### Return type

[**XCommunitiesIdAboutGet200Response**](XCommunitiesIdAboutGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_users_by_get

> <XUsersByGet200Response> x_users_by_get(usernames, opts)

Get X users by usernames

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
usernames = 'usernames_example' # String | Comma-separated usernames.
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example' # String | 
}

begin
  # Get X users by usernames
  result = api_instance.x_users_by_get(usernames, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_users_by_get: #{e}"
end
```

#### Using the x_users_by_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XUsersByGet200Response>, Integer, Hash)> x_users_by_get_with_http_info(usernames, opts)

```ruby
begin
  # Get X users by usernames
  data, status_code, headers = api_instance.x_users_by_get_with_http_info(usernames, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XUsersByGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_users_by_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **usernames** | **String** | Comma-separated usernames. |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |

### Return type

[**XUsersByGet200Response**](XUsersByGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_users_by_username_username_get

> <XUsersIdGet200Response> x_users_by_username_username_get(username, opts)

Get X user by username

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
username = 'username_example' # String | X handle without the leading `@`.
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example' # String | 
}

begin
  # Get X user by username
  result = api_instance.x_users_by_username_username_get(username, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_users_by_username_username_get: #{e}"
end
```

#### Using the x_users_by_username_username_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XUsersIdGet200Response>, Integer, Hash)> x_users_by_username_username_get_with_http_info(username, opts)

```ruby
begin
  # Get X user by username
  data, status_code, headers = api_instance.x_users_by_username_username_get_with_http_info(username, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XUsersIdGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_users_by_username_username_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** | X handle without the leading &#x60;@&#x60;. |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |

### Return type

[**XUsersIdGet200Response**](XUsersIdGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_users_get

> <XUsersByGet200Response> x_users_get(ids, opts)

Get X users by IDs

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
ids = 'ids_example' # String | Comma-separated resource ids.
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example' # String | 
}

begin
  # Get X users by IDs
  result = api_instance.x_users_get(ids, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_users_get: #{e}"
end
```

#### Using the x_users_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XUsersByGet200Response>, Integer, Hash)> x_users_get_with_http_info(ids, opts)

```ruby
begin
  # Get X users by IDs
  data, status_code, headers = api_instance.x_users_get_with_http_info(ids, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XUsersByGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_users_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **ids** | **String** | Comma-separated resource ids. |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |

### Return type

[**XUsersByGet200Response**](XUsersByGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_users_id_followers_get

> <XCommunitiesIdMemberSearchGet200Response> x_users_id_followers_get(id, opts)

Get an X user's followers

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
id = 'id_example' # String | X resource id.
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example', # String | 
  pagination_token: 'pagination_token_example', # String | 
  next_token: 'next_token_example', # String | 
  max_results: 56 # Integer | 
}

begin
  # Get an X user's followers
  result = api_instance.x_users_id_followers_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_users_id_followers_get: #{e}"
end
```

#### Using the x_users_id_followers_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XCommunitiesIdMemberSearchGet200Response>, Integer, Hash)> x_users_id_followers_get_with_http_info(id, opts)

```ruby
begin
  # Get an X user's followers
  data, status_code, headers = api_instance.x_users_id_followers_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XCommunitiesIdMemberSearchGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_users_id_followers_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | X resource id. |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |
| **pagination_token** | **String** |  | [optional] |
| **next_token** | **String** |  | [optional] |
| **max_results** | **Integer** |  | [optional] |

### Return type

[**XCommunitiesIdMemberSearchGet200Response**](XCommunitiesIdMemberSearchGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_users_id_followers_ids_get

> <XUsersIdFollowersIdsGet200Response> x_users_id_followers_ids_get(id, opts)

Get follower IDs for an X user

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
id = 'id_example' # String | X resource id.
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example', # String | 
  pagination_token: 'pagination_token_example', # String | 
  next_token: 'next_token_example', # String | 
  max_results: 56 # Integer | 
}

begin
  # Get follower IDs for an X user
  result = api_instance.x_users_id_followers_ids_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_users_id_followers_ids_get: #{e}"
end
```

#### Using the x_users_id_followers_ids_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XUsersIdFollowersIdsGet200Response>, Integer, Hash)> x_users_id_followers_ids_get_with_http_info(id, opts)

```ruby
begin
  # Get follower IDs for an X user
  data, status_code, headers = api_instance.x_users_id_followers_ids_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XUsersIdFollowersIdsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_users_id_followers_ids_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | X resource id. |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |
| **pagination_token** | **String** |  | [optional] |
| **next_token** | **String** |  | [optional] |
| **max_results** | **Integer** |  | [optional] |

### Return type

[**XUsersIdFollowersIdsGet200Response**](XUsersIdFollowersIdsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_users_id_following_get

> <XCommunitiesIdMemberSearchGet200Response> x_users_id_following_get(id, opts)

Get users followed by an X user

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
id = 'id_example' # String | X resource id.
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example', # String | 
  pagination_token: 'pagination_token_example', # String | 
  next_token: 'next_token_example', # String | 
  max_results: 56 # Integer | 
}

begin
  # Get users followed by an X user
  result = api_instance.x_users_id_following_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_users_id_following_get: #{e}"
end
```

#### Using the x_users_id_following_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XCommunitiesIdMemberSearchGet200Response>, Integer, Hash)> x_users_id_following_get_with_http_info(id, opts)

```ruby
begin
  # Get users followed by an X user
  data, status_code, headers = api_instance.x_users_id_following_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XCommunitiesIdMemberSearchGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_users_id_following_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | X resource id. |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |
| **pagination_token** | **String** |  | [optional] |
| **next_token** | **String** |  | [optional] |
| **max_results** | **Integer** |  | [optional] |

### Return type

[**XCommunitiesIdMemberSearchGet200Response**](XCommunitiesIdMemberSearchGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_users_id_following_ids_get

> <XUsersIdFollowersIdsGet200Response> x_users_id_following_ids_get(id, opts)

Get following IDs for an X user

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
id = 'id_example' # String | X resource id.
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example', # String | 
  pagination_token: 'pagination_token_example', # String | 
  next_token: 'next_token_example', # String | 
  max_results: 56 # Integer | 
}

begin
  # Get following IDs for an X user
  result = api_instance.x_users_id_following_ids_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_users_id_following_ids_get: #{e}"
end
```

#### Using the x_users_id_following_ids_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XUsersIdFollowersIdsGet200Response>, Integer, Hash)> x_users_id_following_ids_get_with_http_info(id, opts)

```ruby
begin
  # Get following IDs for an X user
  data, status_code, headers = api_instance.x_users_id_following_ids_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XUsersIdFollowersIdsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_users_id_following_ids_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | X resource id. |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |
| **pagination_token** | **String** |  | [optional] |
| **next_token** | **String** |  | [optional] |
| **max_results** | **Integer** |  | [optional] |

### Return type

[**XUsersIdFollowersIdsGet200Response**](XUsersIdFollowersIdsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_users_id_get

> <XUsersIdGet200Response> x_users_id_get(id, opts)

Get X user by ID

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
id = 'id_example' # String | X resource id.
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example' # String | 
}

begin
  # Get X user by ID
  result = api_instance.x_users_id_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_users_id_get: #{e}"
end
```

#### Using the x_users_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XUsersIdGet200Response>, Integer, Hash)> x_users_id_get_with_http_info(id, opts)

```ruby
begin
  # Get X user by ID
  data, status_code, headers = api_instance.x_users_id_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XUsersIdGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_users_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | X resource id. |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |

### Return type

[**XUsersIdGet200Response**](XUsersIdGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_users_id_liked_tweets_get

> <XCommunitiesIdAboutGet200Response> x_users_id_liked_tweets_get(id, opts)

Get Posts liked by an X user

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
id = 'id_example' # String | X resource id.
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example', # String | 
  pagination_token: 'pagination_token_example', # String | 
  next_token: 'next_token_example', # String | 
  max_results: 56 # Integer | 
}

begin
  # Get Posts liked by an X user
  result = api_instance.x_users_id_liked_tweets_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_users_id_liked_tweets_get: #{e}"
end
```

#### Using the x_users_id_liked_tweets_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XCommunitiesIdAboutGet200Response>, Integer, Hash)> x_users_id_liked_tweets_get_with_http_info(id, opts)

```ruby
begin
  # Get Posts liked by an X user
  data, status_code, headers = api_instance.x_users_id_liked_tweets_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XCommunitiesIdAboutGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_users_id_liked_tweets_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | X resource id. |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |
| **pagination_token** | **String** |  | [optional] |
| **next_token** | **String** |  | [optional] |
| **max_results** | **Integer** |  | [optional] |

### Return type

[**XCommunitiesIdAboutGet200Response**](XCommunitiesIdAboutGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_users_id_profile_translation_get

> <XTweetsIdTranslationGet200Response> x_users_id_profile_translation_get(id, language)

Translate an X user profile

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
id = 'id_example' # String | X resource id.
language = 'language_example' # String | 

begin
  # Translate an X user profile
  result = api_instance.x_users_id_profile_translation_get(id, language)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_users_id_profile_translation_get: #{e}"
end
```

#### Using the x_users_id_profile_translation_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XTweetsIdTranslationGet200Response>, Integer, Hash)> x_users_id_profile_translation_get_with_http_info(id, language)

```ruby
begin
  # Translate an X user profile
  data, status_code, headers = api_instance.x_users_id_profile_translation_get_with_http_info(id, language)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XTweetsIdTranslationGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_users_id_profile_translation_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | X resource id. |  |
| **language** | **String** |  |  |

### Return type

[**XTweetsIdTranslationGet200Response**](XTweetsIdTranslationGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_users_id_tweets_get

> <XCommunitiesIdAboutGet200Response> x_users_id_tweets_get(id, opts)

Get Posts authored by an X user

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
id = 'id_example' # String | X resource id.
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example', # String | 
  pagination_token: 'pagination_token_example', # String | 
  next_token: 'next_token_example', # String | 
  max_results: 56, # Integer | 
  exclude: 'exclude_example' # String | Comma-separated X timeline exclusions, e.g. `replies`.
}

begin
  # Get Posts authored by an X user
  result = api_instance.x_users_id_tweets_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_users_id_tweets_get: #{e}"
end
```

#### Using the x_users_id_tweets_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XCommunitiesIdAboutGet200Response>, Integer, Hash)> x_users_id_tweets_get_with_http_info(id, opts)

```ruby
begin
  # Get Posts authored by an X user
  data, status_code, headers = api_instance.x_users_id_tweets_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XCommunitiesIdAboutGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_users_id_tweets_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | X resource id. |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |
| **pagination_token** | **String** |  | [optional] |
| **next_token** | **String** |  | [optional] |
| **max_results** | **Integer** |  | [optional] |
| **exclude** | **String** | Comma-separated X timeline exclusions, e.g. &#x60;replies&#x60;. | [optional] |

### Return type

[**XCommunitiesIdAboutGet200Response**](XCommunitiesIdAboutGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## x_users_id_verified_followers_get

> <XCommunitiesIdMemberSearchGet200Response> x_users_id_verified_followers_get(id, opts)

Get verified followers for an X user

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::XApi.new
id = 'id_example' # String | X resource id.
opts = {
  expansions: 'expansions_example', # String | 
  tweet_fields: 'tweet_fields_example', # String | 
  user_fields: 'user_fields_example', # String | 
  media_fields: 'media_fields_example', # String | 
  place_fields: 'place_fields_example', # String | 
  poll_fields: 'poll_fields_example', # String | 
  pagination_token: 'pagination_token_example', # String | 
  next_token: 'next_token_example', # String | 
  max_results: 56 # Integer | 
}

begin
  # Get verified followers for an X user
  result = api_instance.x_users_id_verified_followers_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_users_id_verified_followers_get: #{e}"
end
```

#### Using the x_users_id_verified_followers_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<XCommunitiesIdMemberSearchGet200Response>, Integer, Hash)> x_users_id_verified_followers_get_with_http_info(id, opts)

```ruby
begin
  # Get verified followers for an X user
  data, status_code, headers = api_instance.x_users_id_verified_followers_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <XCommunitiesIdMemberSearchGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling XApi->x_users_id_verified_followers_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | X resource id. |  |
| **expansions** | **String** |  | [optional] |
| **tweet_fields** | **String** |  | [optional] |
| **user_fields** | **String** |  | [optional] |
| **media_fields** | **String** |  | [optional] |
| **place_fields** | **String** |  | [optional] |
| **poll_fields** | **String** |  | [optional] |
| **pagination_token** | **String** |  | [optional] |
| **next_token** | **String** |  | [optional] |
| **max_results** | **Integer** |  | [optional] |

### Return type

[**XCommunitiesIdMemberSearchGet200Response**](XCommunitiesIdMemberSearchGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

