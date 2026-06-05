# Unifapi::MapsApi

All URIs are relative to *https://api.unifapi.com*

| Method | HTTP request | Description |
| ------ | ------------ | ----------- |
| [**maps_search_post**](MapsApi.md#maps_search_post) | **POST** /maps/search | Search Maps |


## maps_search_post

> <MapsSearchPost200Response> maps_search_post(opts)

Search Maps

Run one live Maps search and receive ranked local business listings for a query, including title, address, rating, category, phone, coordinates, and place id.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::MapsApi.new
opts = {
  maps_search_request: Unifapi::MapsSearchRequest.new({query: 'query_example'}) # MapsSearchRequest | 
}

begin
  # Search Maps
  result = api_instance.maps_search_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling MapsApi->maps_search_post: #{e}"
end
```

#### Using the maps_search_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<MapsSearchPost200Response>, Integer, Hash)> maps_search_post_with_http_info(opts)

```ruby
begin
  # Search Maps
  data, status_code, headers = api_instance.maps_search_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <MapsSearchPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling MapsApi->maps_search_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **maps_search_request** | [**MapsSearchRequest**](MapsSearchRequest.md) |  | [optional] |

### Return type

[**MapsSearchPost200Response**](MapsSearchPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

