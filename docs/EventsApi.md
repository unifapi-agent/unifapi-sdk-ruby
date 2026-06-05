# Unifapi::EventsApi

All URIs are relative to *https://api.unifapi.com*

| Method | HTTP request | Description |
| ------ | ------------ | ----------- |
| [**events_search_post**](EventsApi.md#events_search_post) | **POST** /events/search | Search Events |


## events_search_post

> <EventsSearchPost200Response> events_search_post(opts)

Search Events

Run one live Events search and receive individual events for a query, including title, dates, venue location, ticket links, and a description.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::EventsApi.new
opts = {
  events_search_request: Unifapi::EventsSearchRequest.new({query: 'query_example'}) # EventsSearchRequest | 
}

begin
  # Search Events
  result = api_instance.events_search_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling EventsApi->events_search_post: #{e}"
end
```

#### Using the events_search_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<EventsSearchPost200Response>, Integer, Hash)> events_search_post_with_http_info(opts)

```ruby
begin
  # Search Events
  data, status_code, headers = api_instance.events_search_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <EventsSearchPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling EventsApi->events_search_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **events_search_request** | [**EventsSearchRequest**](EventsSearchRequest.md) |  | [optional] |

### Return type

[**EventsSearchPost200Response**](EventsSearchPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

