# Unifapi::NewsApi

All URIs are relative to *https://api.unifapi.com*

| Method | HTTP request | Description |
| ------ | ------------ | ----------- |
| [**news_search_post**](NewsApi.md#news_search_post) | **POST** /news/search | Search News |


## news_search_post

> <NewsSearchPost200Response> news_search_post(opts)

Search News

Run one live News search and receive the ranked news articles and top-stories blocks for a query, including title, publisher domain, snippet, image, and publish time.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::NewsApi.new
opts = {
  news_search_request: Unifapi::NewsSearchRequest.new({query: 'query_example'}) # NewsSearchRequest | 
}

begin
  # Search News
  result = api_instance.news_search_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling NewsApi->news_search_post: #{e}"
end
```

#### Using the news_search_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<NewsSearchPost200Response>, Integer, Hash)> news_search_post_with_http_info(opts)

```ruby
begin
  # Search News
  data, status_code, headers = api_instance.news_search_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <NewsSearchPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling NewsApi->news_search_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **news_search_request** | [**NewsSearchRequest**](NewsSearchRequest.md) |  | [optional] |

### Return type

[**NewsSearchPost200Response**](NewsSearchPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

