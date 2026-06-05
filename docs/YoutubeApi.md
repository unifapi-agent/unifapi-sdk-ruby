# Unifapi::YoutubeApi

All URIs are relative to *https://api.unifapi.com*

| Method | HTTP request | Description |
| ------ | ------------ | ----------- |
| [**youtube_channels_channel_id_get**](YoutubeApi.md#youtube_channels_channel_id_get) | **GET** /youtube/channels/{channel_id} | Get a YouTube channel by id |
| [**youtube_channels_channel_id_shorts_get**](YoutubeApi.md#youtube_channels_channel_id_shorts_get) | **GET** /youtube/channels/{channel_id}/shorts | List Shorts uploaded by a YouTube channel |
| [**youtube_channels_channel_id_videos_get**](YoutubeApi.md#youtube_channels_channel_id_videos_get) | **GET** /youtube/channels/{channel_id}/videos | List videos uploaded by a YouTube channel |
| [**youtube_resolve_channel_id_get**](YoutubeApi.md#youtube_resolve_channel_id_get) | **GET** /youtube/resolve/channel-id | Resolve a YouTube channel URL to its UC… channel id |
| [**youtube_search_get**](YoutubeApi.md#youtube_search_get) | **GET** /youtube/search | Search YouTube videos by keyword |
| [**youtube_trending_get**](YoutubeApi.md#youtube_trending_get) | **GET** /youtube/trending | Browse YouTube&#39;s trending videos |
| [**youtube_videos_video_id_get**](YoutubeApi.md#youtube_videos_video_id_get) | **GET** /youtube/videos/{video_id} | Get a YouTube video by id |
| [**youtube_videos_video_id_related_get**](YoutubeApi.md#youtube_videos_video_id_related_get) | **GET** /youtube/videos/{video_id}/related | List YouTube videos related to a given video |


## youtube_channels_channel_id_get

> <YoutubeChannelsChannelIdGet200Response> youtube_channels_channel_id_get(channel_id)

Get a YouTube channel by id

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::YoutubeApi.new
channel_id = 'channel_id_example' # String | YouTube channel id (`UCxxx...`).

begin
  # Get a YouTube channel by id
  result = api_instance.youtube_channels_channel_id_get(channel_id)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling YoutubeApi->youtube_channels_channel_id_get: #{e}"
end
```

#### Using the youtube_channels_channel_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<YoutubeChannelsChannelIdGet200Response>, Integer, Hash)> youtube_channels_channel_id_get_with_http_info(channel_id)

```ruby
begin
  # Get a YouTube channel by id
  data, status_code, headers = api_instance.youtube_channels_channel_id_get_with_http_info(channel_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <YoutubeChannelsChannelIdGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling YoutubeApi->youtube_channels_channel_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **channel_id** | **String** | YouTube channel id (&#x60;UCxxx...&#x60;). |  |

### Return type

[**YoutubeChannelsChannelIdGet200Response**](YoutubeChannelsChannelIdGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## youtube_channels_channel_id_shorts_get

> <YoutubeChannelsChannelIdShortsGet200Response> youtube_channels_channel_id_shorts_get(channel_id, opts)

List Shorts uploaded by a YouTube channel

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::YoutubeApi.new
channel_id = 'channel_id_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List Shorts uploaded by a YouTube channel
  result = api_instance.youtube_channels_channel_id_shorts_get(channel_id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling YoutubeApi->youtube_channels_channel_id_shorts_get: #{e}"
end
```

#### Using the youtube_channels_channel_id_shorts_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<YoutubeChannelsChannelIdShortsGet200Response>, Integer, Hash)> youtube_channels_channel_id_shorts_get_with_http_info(channel_id, opts)

```ruby
begin
  # List Shorts uploaded by a YouTube channel
  data, status_code, headers = api_instance.youtube_channels_channel_id_shorts_get_with_http_info(channel_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <YoutubeChannelsChannelIdShortsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling YoutubeApi->youtube_channels_channel_id_shorts_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **channel_id** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**YoutubeChannelsChannelIdShortsGet200Response**](YoutubeChannelsChannelIdShortsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## youtube_channels_channel_id_videos_get

> <YoutubeChannelsChannelIdShortsGet200Response> youtube_channels_channel_id_videos_get(channel_id, opts)

List videos uploaded by a YouTube channel

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::YoutubeApi.new
channel_id = 'channel_id_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List videos uploaded by a YouTube channel
  result = api_instance.youtube_channels_channel_id_videos_get(channel_id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling YoutubeApi->youtube_channels_channel_id_videos_get: #{e}"
end
```

#### Using the youtube_channels_channel_id_videos_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<YoutubeChannelsChannelIdShortsGet200Response>, Integer, Hash)> youtube_channels_channel_id_videos_get_with_http_info(channel_id, opts)

```ruby
begin
  # List videos uploaded by a YouTube channel
  data, status_code, headers = api_instance.youtube_channels_channel_id_videos_get_with_http_info(channel_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <YoutubeChannelsChannelIdShortsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling YoutubeApi->youtube_channels_channel_id_videos_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **channel_id** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**YoutubeChannelsChannelIdShortsGet200Response**](YoutubeChannelsChannelIdShortsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## youtube_resolve_channel_id_get

> <YoutubeResolveChannelIdGet200Response> youtube_resolve_channel_id_get(url)

Resolve a YouTube channel URL to its UC… channel id

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::YoutubeApi.new
url = 'url_example' # String | Full channel URL — supports `youtube.com/@handle`, `/channel/UC…`, `/c/name`.

begin
  # Resolve a YouTube channel URL to its UC… channel id
  result = api_instance.youtube_resolve_channel_id_get(url)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling YoutubeApi->youtube_resolve_channel_id_get: #{e}"
end
```

#### Using the youtube_resolve_channel_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<YoutubeResolveChannelIdGet200Response>, Integer, Hash)> youtube_resolve_channel_id_get_with_http_info(url)

```ruby
begin
  # Resolve a YouTube channel URL to its UC… channel id
  data, status_code, headers = api_instance.youtube_resolve_channel_id_get_with_http_info(url)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <YoutubeResolveChannelIdGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling YoutubeApi->youtube_resolve_channel_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **url** | **String** | Full channel URL — supports &#x60;youtube.com/@handle&#x60;, &#x60;/channel/UC…&#x60;, &#x60;/c/name&#x60;. |  |

### Return type

[**YoutubeResolveChannelIdGet200Response**](YoutubeResolveChannelIdGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## youtube_search_get

> <YoutubeChannelsChannelIdShortsGet200Response> youtube_search_get(q, opts)

Search YouTube videos by keyword

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::YoutubeApi.new
q = 'q_example' # String | Search keyword.
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # Search YouTube videos by keyword
  result = api_instance.youtube_search_get(q, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling YoutubeApi->youtube_search_get: #{e}"
end
```

#### Using the youtube_search_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<YoutubeChannelsChannelIdShortsGet200Response>, Integer, Hash)> youtube_search_get_with_http_info(q, opts)

```ruby
begin
  # Search YouTube videos by keyword
  data, status_code, headers = api_instance.youtube_search_get_with_http_info(q, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <YoutubeChannelsChannelIdShortsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling YoutubeApi->youtube_search_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **q** | **String** | Search keyword. |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**YoutubeChannelsChannelIdShortsGet200Response**](YoutubeChannelsChannelIdShortsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## youtube_trending_get

> <YoutubeTrendingGet200Response> youtube_trending_get(opts)

Browse YouTube's trending videos

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::YoutubeApi.new
opts = {
  language_code: 'language_code_example' # String | Optional language code, e.g. `en`.
}

begin
  # Browse YouTube's trending videos
  result = api_instance.youtube_trending_get(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling YoutubeApi->youtube_trending_get: #{e}"
end
```

#### Using the youtube_trending_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<YoutubeTrendingGet200Response>, Integer, Hash)> youtube_trending_get_with_http_info(opts)

```ruby
begin
  # Browse YouTube's trending videos
  data, status_code, headers = api_instance.youtube_trending_get_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <YoutubeTrendingGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling YoutubeApi->youtube_trending_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **language_code** | **String** | Optional language code, e.g. &#x60;en&#x60;. | [optional] |

### Return type

[**YoutubeTrendingGet200Response**](YoutubeTrendingGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## youtube_videos_video_id_get

> <YoutubeVideosVideoIdGet200Response> youtube_videos_video_id_get(video_id)

Get a YouTube video by id

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::YoutubeApi.new
video_id = 'video_id_example' # String | YouTube video id, e.g. `oaSNBz4qMQY`.

begin
  # Get a YouTube video by id
  result = api_instance.youtube_videos_video_id_get(video_id)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling YoutubeApi->youtube_videos_video_id_get: #{e}"
end
```

#### Using the youtube_videos_video_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<YoutubeVideosVideoIdGet200Response>, Integer, Hash)> youtube_videos_video_id_get_with_http_info(video_id)

```ruby
begin
  # Get a YouTube video by id
  data, status_code, headers = api_instance.youtube_videos_video_id_get_with_http_info(video_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <YoutubeVideosVideoIdGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling YoutubeApi->youtube_videos_video_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **video_id** | **String** | YouTube video id, e.g. &#x60;oaSNBz4qMQY&#x60;. |  |

### Return type

[**YoutubeVideosVideoIdGet200Response**](YoutubeVideosVideoIdGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## youtube_videos_video_id_related_get

> <YoutubeChannelsChannelIdShortsGet200Response> youtube_videos_video_id_related_get(video_id, opts)

List YouTube videos related to a given video

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::YoutubeApi.new
video_id = 'video_id_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List YouTube videos related to a given video
  result = api_instance.youtube_videos_video_id_related_get(video_id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling YoutubeApi->youtube_videos_video_id_related_get: #{e}"
end
```

#### Using the youtube_videos_video_id_related_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<YoutubeChannelsChannelIdShortsGet200Response>, Integer, Hash)> youtube_videos_video_id_related_get_with_http_info(video_id, opts)

```ruby
begin
  # List YouTube videos related to a given video
  data, status_code, headers = api_instance.youtube_videos_video_id_related_get_with_http_info(video_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <YoutubeChannelsChannelIdShortsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling YoutubeApi->youtube_videos_video_id_related_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **video_id** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**YoutubeChannelsChannelIdShortsGet200Response**](YoutubeChannelsChannelIdShortsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

