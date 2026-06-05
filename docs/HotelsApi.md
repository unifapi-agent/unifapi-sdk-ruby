# Unifapi::HotelsApi

All URIs are relative to *https://api.unifapi.com*

| Method | HTTP request | Description |
| ------ | ------------ | ----------- |
| [**hotels_info_post**](HotelsApi.md#hotels_info_post) | **POST** /hotels/info | Get Hotels detail |
| [**hotels_search_post**](HotelsApi.md#hotels_search_post) | **POST** /hotels/search | Search Hotels |


## hotels_info_post

> <HotelsInfoPost200Response> hotels_info_post(opts)

Get Hotels detail

Run one live Hotels detail lookup for a hotel id from /hotels/search and receive the full profile, including class rating, address, phone, description, guest reviews, images, and prices.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::HotelsApi.new
opts = {
  hotel_info_request: Unifapi::HotelInfoRequest.new({hotel_identifier: 'hotel_identifier_example'}) # HotelInfoRequest | 
}

begin
  # Get Hotels detail
  result = api_instance.hotels_info_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling HotelsApi->hotels_info_post: #{e}"
end
```

#### Using the hotels_info_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<HotelsInfoPost200Response>, Integer, Hash)> hotels_info_post_with_http_info(opts)

```ruby
begin
  # Get Hotels detail
  data, status_code, headers = api_instance.hotels_info_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <HotelsInfoPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling HotelsApi->hotels_info_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **hotel_info_request** | [**HotelInfoRequest**](HotelInfoRequest.md) |  | [optional] |

### Return type

[**HotelsInfoPost200Response**](HotelsInfoPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## hotels_search_post

> <HotelsSearchPost200Response> hotels_search_post(opts)

Search Hotels

Run one live Hotels search and receive ranked hotel listings for a location and stay dates, including hotel id, class rating, guest reviews, and nightly prices. Pass a hotel id to /hotels/info for full details.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::HotelsApi.new
opts = {
  hotel_search_request: Unifapi::HotelSearchRequest.new # HotelSearchRequest | 
}

begin
  # Search Hotels
  result = api_instance.hotels_search_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling HotelsApi->hotels_search_post: #{e}"
end
```

#### Using the hotels_search_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<HotelsSearchPost200Response>, Integer, Hash)> hotels_search_post_with_http_info(opts)

```ruby
begin
  # Search Hotels
  data, status_code, headers = api_instance.hotels_search_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <HotelsSearchPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling HotelsApi->hotels_search_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **hotel_search_request** | [**HotelSearchRequest**](HotelSearchRequest.md) |  | [optional] |

### Return type

[**HotelsSearchPost200Response**](HotelsSearchPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

