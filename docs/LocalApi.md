# Unifapi::LocalApi

All URIs are relative to *https://api.unifapi.com*

| Method | HTTP request | Description |
| ------ | ------------ | ----------- |
| [**local_search_post**](LocalApi.md#local_search_post) | **POST** /local/search | Search Local Finder |


## local_search_post

> <LocalSearchPost200Response> local_search_post(opts)

Search Local Finder

Run one live Local Finder search — the expanded local-pack listing — and receive ranked local places for a query, including title, address, rating, phone, and booking links.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LocalApi.new
opts = {
  local_finder_request: Unifapi::LocalFinderRequest.new({query: 'query_example'}) # LocalFinderRequest | 
}

begin
  # Search Local Finder
  result = api_instance.local_search_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LocalApi->local_search_post: #{e}"
end
```

#### Using the local_search_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LocalSearchPost200Response>, Integer, Hash)> local_search_post_with_http_info(opts)

```ruby
begin
  # Search Local Finder
  data, status_code, headers = api_instance.local_search_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LocalSearchPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LocalApi->local_search_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **local_finder_request** | [**LocalFinderRequest**](LocalFinderRequest.md) |  | [optional] |

### Return type

[**LocalSearchPost200Response**](LocalSearchPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

