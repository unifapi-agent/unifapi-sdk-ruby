# Unifapi::ThreadsApi

All URIs are relative to *https://api.unifapi.com*

| Method | HTTP request | Description |
| ------ | ------------ | ----------- |
| [**threads_search_profiles_get**](ThreadsApi.md#threads_search_profiles_get) | **GET** /threads/search/profiles | Search Threads users by keyword |
| [**threads_search_recent_get**](ThreadsApi.md#threads_search_recent_get) | **GET** /threads/search/recent | Search recent Threads posts |
| [**threads_search_top_get**](ThreadsApi.md#threads_search_top_get) | **GET** /threads/search/top | Search top Threads posts |
| [**threads_users_username_get**](ThreadsApi.md#threads_users_username_get) | **GET** /threads/users/{username} | Get a Threads user profile by username |
| [**threads_users_username_posts_get**](ThreadsApi.md#threads_users_username_posts_get) | **GET** /threads/users/{username}/posts | List Threads posts authored by a user |
| [**threads_users_username_replies_get**](ThreadsApi.md#threads_users_username_replies_get) | **GET** /threads/users/{username}/replies | List Threads replies authored by a user |
| [**threads_users_username_reposts_get**](ThreadsApi.md#threads_users_username_reposts_get) | **GET** /threads/users/{username}/reposts | List Threads reposts by a user |


## threads_search_profiles_get

> <ThreadsSearchProfilesGet200Response> threads_search_profiles_get(q)

Search Threads users by keyword

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::ThreadsApi.new
q = 'q_example' # String | Search keyword.

begin
  # Search Threads users by keyword
  result = api_instance.threads_search_profiles_get(q)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling ThreadsApi->threads_search_profiles_get: #{e}"
end
```

#### Using the threads_search_profiles_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ThreadsSearchProfilesGet200Response>, Integer, Hash)> threads_search_profiles_get_with_http_info(q)

```ruby
begin
  # Search Threads users by keyword
  data, status_code, headers = api_instance.threads_search_profiles_get_with_http_info(q)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ThreadsSearchProfilesGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling ThreadsApi->threads_search_profiles_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **q** | **String** | Search keyword. |  |

### Return type

[**ThreadsSearchProfilesGet200Response**](ThreadsSearchProfilesGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## threads_search_recent_get

> <ThreadsSearchRecentGet200Response> threads_search_recent_get(q, opts)

Search recent Threads posts

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::ThreadsApi.new
q = 'q_example' # String | Search keyword.
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # Search recent Threads posts
  result = api_instance.threads_search_recent_get(q, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling ThreadsApi->threads_search_recent_get: #{e}"
end
```

#### Using the threads_search_recent_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ThreadsSearchRecentGet200Response>, Integer, Hash)> threads_search_recent_get_with_http_info(q, opts)

```ruby
begin
  # Search recent Threads posts
  data, status_code, headers = api_instance.threads_search_recent_get_with_http_info(q, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ThreadsSearchRecentGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling ThreadsApi->threads_search_recent_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **q** | **String** | Search keyword. |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**ThreadsSearchRecentGet200Response**](ThreadsSearchRecentGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## threads_search_top_get

> <ThreadsSearchRecentGet200Response> threads_search_top_get(q, opts)

Search top Threads posts

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::ThreadsApi.new
q = 'q_example' # String | Search keyword.
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # Search top Threads posts
  result = api_instance.threads_search_top_get(q, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling ThreadsApi->threads_search_top_get: #{e}"
end
```

#### Using the threads_search_top_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ThreadsSearchRecentGet200Response>, Integer, Hash)> threads_search_top_get_with_http_info(q, opts)

```ruby
begin
  # Search top Threads posts
  data, status_code, headers = api_instance.threads_search_top_get_with_http_info(q, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ThreadsSearchRecentGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling ThreadsApi->threads_search_top_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **q** | **String** | Search keyword. |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**ThreadsSearchRecentGet200Response**](ThreadsSearchRecentGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## threads_users_username_get

> <ThreadsUsersUsernameGet200Response> threads_users_username_get(username)

Get a Threads user profile by username

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::ThreadsApi.new
username = 'username_example' # String | 

begin
  # Get a Threads user profile by username
  result = api_instance.threads_users_username_get(username)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling ThreadsApi->threads_users_username_get: #{e}"
end
```

#### Using the threads_users_username_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ThreadsUsersUsernameGet200Response>, Integer, Hash)> threads_users_username_get_with_http_info(username)

```ruby
begin
  # Get a Threads user profile by username
  data, status_code, headers = api_instance.threads_users_username_get_with_http_info(username)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ThreadsUsersUsernameGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling ThreadsApi->threads_users_username_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |

### Return type

[**ThreadsUsersUsernameGet200Response**](ThreadsUsersUsernameGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## threads_users_username_posts_get

> <ThreadsSearchRecentGet200Response> threads_users_username_posts_get(username, opts)

List Threads posts authored by a user

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::ThreadsApi.new
username = 'username_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List Threads posts authored by a user
  result = api_instance.threads_users_username_posts_get(username, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling ThreadsApi->threads_users_username_posts_get: #{e}"
end
```

#### Using the threads_users_username_posts_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ThreadsSearchRecentGet200Response>, Integer, Hash)> threads_users_username_posts_get_with_http_info(username, opts)

```ruby
begin
  # List Threads posts authored by a user
  data, status_code, headers = api_instance.threads_users_username_posts_get_with_http_info(username, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ThreadsSearchRecentGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling ThreadsApi->threads_users_username_posts_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**ThreadsSearchRecentGet200Response**](ThreadsSearchRecentGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## threads_users_username_replies_get

> <ThreadsSearchRecentGet200Response> threads_users_username_replies_get(username, opts)

List Threads replies authored by a user

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::ThreadsApi.new
username = 'username_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List Threads replies authored by a user
  result = api_instance.threads_users_username_replies_get(username, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling ThreadsApi->threads_users_username_replies_get: #{e}"
end
```

#### Using the threads_users_username_replies_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ThreadsSearchRecentGet200Response>, Integer, Hash)> threads_users_username_replies_get_with_http_info(username, opts)

```ruby
begin
  # List Threads replies authored by a user
  data, status_code, headers = api_instance.threads_users_username_replies_get_with_http_info(username, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ThreadsSearchRecentGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling ThreadsApi->threads_users_username_replies_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**ThreadsSearchRecentGet200Response**](ThreadsSearchRecentGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## threads_users_username_reposts_get

> <ThreadsSearchRecentGet200Response> threads_users_username_reposts_get(username, opts)

List Threads reposts by a user

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::ThreadsApi.new
username = 'username_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List Threads reposts by a user
  result = api_instance.threads_users_username_reposts_get(username, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling ThreadsApi->threads_users_username_reposts_get: #{e}"
end
```

#### Using the threads_users_username_reposts_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ThreadsSearchRecentGet200Response>, Integer, Hash)> threads_users_username_reposts_get_with_http_info(username, opts)

```ruby
begin
  # List Threads reposts by a user
  data, status_code, headers = api_instance.threads_users_username_reposts_get_with_http_info(username, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ThreadsSearchRecentGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling ThreadsApi->threads_users_username_reposts_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**ThreadsSearchRecentGet200Response**](ThreadsSearchRecentGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

