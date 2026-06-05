# Unifapi::GeoApi

All URIs are relative to *https://api.unifapi.com*

| Method | HTTP request | Description |
| ------ | ------------ | ----------- |
| [**geo_keywords_search_volume_post**](GeoApi.md#geo_keywords_search_volume_post) | **POST** /geo/keywords/search-volume | Get AI search volume for keywords |
| [**geo_mentions_aggregated_metrics_post**](GeoApi.md#geo_mentions_aggregated_metrics_post) | **POST** /geo/mentions/aggregated-metrics | Aggregate LLM mention metrics by dimension |
| [**geo_mentions_cross_aggregated_metrics_post**](GeoApi.md#geo_mentions_cross_aggregated_metrics_post) | **POST** /geo/mentions/cross-aggregated-metrics | Compare LLM mentions across labeled groups |
| [**geo_mentions_search_post**](GeoApi.md#geo_mentions_search_post) | **POST** /geo/mentions/search | Search LLM mentions of a domain or keyword |
| [**geo_mentions_top_domains_post**](GeoApi.md#geo_mentions_top_domains_post) | **POST** /geo/mentions/top-domains | List domains most cited in LLM answers |
| [**geo_mentions_top_pages_post**](GeoApi.md#geo_mentions_top_pages_post) | **POST** /geo/mentions/top-pages | List pages most cited in LLM answers |
| [**geo_serp_post**](GeoApi.md#geo_serp_post) | **POST** /geo/serp | Search AI Mode generative results |


## geo_keywords_search_volume_post

> <GeoKeywordsSearchVolumePost200Response> geo_keywords_search_volume_post(opts)

Get AI search volume for keywords

Look up generative-AI search volume and monthly trend for up to 1000 keywords in a location and language.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::GeoApi.new
opts = {
  geo_keyword_search_volume_request: Unifapi::GeoKeywordSearchVolumeRequest.new({keywords: ['keywords_example']}) # GeoKeywordSearchVolumeRequest | 
}

begin
  # Get AI search volume for keywords
  result = api_instance.geo_keywords_search_volume_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling GeoApi->geo_keywords_search_volume_post: #{e}"
end
```

#### Using the geo_keywords_search_volume_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GeoKeywordsSearchVolumePost200Response>, Integer, Hash)> geo_keywords_search_volume_post_with_http_info(opts)

```ruby
begin
  # Get AI search volume for keywords
  data, status_code, headers = api_instance.geo_keywords_search_volume_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GeoKeywordsSearchVolumePost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling GeoApi->geo_keywords_search_volume_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **geo_keyword_search_volume_request** | [**GeoKeywordSearchVolumeRequest**](GeoKeywordSearchVolumeRequest.md) |  | [optional] |

### Return type

[**GeoKeywordsSearchVolumePost200Response**](GeoKeywordsSearchVolumePost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## geo_mentions_aggregated_metrics_post

> <GeoMentionsAggregatedMetricsPost200Response> geo_mentions_aggregated_metrics_post(opts)

Aggregate LLM mention metrics by dimension

Aggregate LLM mentions of a domain or keyword across platform, location, language, source/search-result domains, and brand entities.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::GeoApi.new
opts = {
  geo_mentions_aggregated_metrics_request: Unifapi::GeoMentionsAggregatedMetricsRequest.new({target: [Unifapi::GeoMentionsTarget.new]}) # GeoMentionsAggregatedMetricsRequest | 
}

begin
  # Aggregate LLM mention metrics by dimension
  result = api_instance.geo_mentions_aggregated_metrics_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling GeoApi->geo_mentions_aggregated_metrics_post: #{e}"
end
```

#### Using the geo_mentions_aggregated_metrics_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GeoMentionsAggregatedMetricsPost200Response>, Integer, Hash)> geo_mentions_aggregated_metrics_post_with_http_info(opts)

```ruby
begin
  # Aggregate LLM mention metrics by dimension
  data, status_code, headers = api_instance.geo_mentions_aggregated_metrics_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GeoMentionsAggregatedMetricsPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling GeoApi->geo_mentions_aggregated_metrics_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **geo_mentions_aggregated_metrics_request** | [**GeoMentionsAggregatedMetricsRequest**](GeoMentionsAggregatedMetricsRequest.md) |  | [optional] |

### Return type

[**GeoMentionsAggregatedMetricsPost200Response**](GeoMentionsAggregatedMetricsPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## geo_mentions_cross_aggregated_metrics_post

> <GeoMentionsCrossAggregatedMetricsPost200Response> geo_mentions_cross_aggregated_metrics_post(opts)

Compare LLM mentions across labeled groups

Aggregate and compare LLM mention metrics across several labeled target groups for side-by-side share-of-voice analysis.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::GeoApi.new
opts = {
  geo_mentions_cross_aggregated_metrics_request: Unifapi::GeoMentionsCrossAggregatedMetricsRequest.new({groups: [Unifapi::GeoMentionsCrossGroup.new({label: 'label_example', target: [Unifapi::GeoMentionsTarget.new]})]}) # GeoMentionsCrossAggregatedMetricsRequest | 
}

begin
  # Compare LLM mentions across labeled groups
  result = api_instance.geo_mentions_cross_aggregated_metrics_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling GeoApi->geo_mentions_cross_aggregated_metrics_post: #{e}"
end
```

#### Using the geo_mentions_cross_aggregated_metrics_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GeoMentionsCrossAggregatedMetricsPost200Response>, Integer, Hash)> geo_mentions_cross_aggregated_metrics_post_with_http_info(opts)

```ruby
begin
  # Compare LLM mentions across labeled groups
  data, status_code, headers = api_instance.geo_mentions_cross_aggregated_metrics_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GeoMentionsCrossAggregatedMetricsPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling GeoApi->geo_mentions_cross_aggregated_metrics_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **geo_mentions_cross_aggregated_metrics_request** | [**GeoMentionsCrossAggregatedMetricsRequest**](GeoMentionsCrossAggregatedMetricsRequest.md) |  | [optional] |

### Return type

[**GeoMentionsCrossAggregatedMetricsPost200Response**](GeoMentionsCrossAggregatedMetricsPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## geo_mentions_search_post

> <GeoMentionsSearchPost200Response> geo_mentions_search_post(opts)

Search LLM mentions of a domain or keyword

Find where a domain or keyword is mentioned across ChatGPT and AI search answers, with the question, answer, cited sources, and AI search volume.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::GeoApi.new
opts = {
  geo_mentions_search_request: Unifapi::GeoMentionsSearchRequest.new({target: [Unifapi::GeoMentionsTarget.new]}) # GeoMentionsSearchRequest | 
}

begin
  # Search LLM mentions of a domain or keyword
  result = api_instance.geo_mentions_search_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling GeoApi->geo_mentions_search_post: #{e}"
end
```

#### Using the geo_mentions_search_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GeoMentionsSearchPost200Response>, Integer, Hash)> geo_mentions_search_post_with_http_info(opts)

```ruby
begin
  # Search LLM mentions of a domain or keyword
  data, status_code, headers = api_instance.geo_mentions_search_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GeoMentionsSearchPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling GeoApi->geo_mentions_search_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **geo_mentions_search_request** | [**GeoMentionsSearchRequest**](GeoMentionsSearchRequest.md) |  | [optional] |

### Return type

[**GeoMentionsSearchPost200Response**](GeoMentionsSearchPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## geo_mentions_top_domains_post

> <GeoMentionsTopDomainsPost200Response> geo_mentions_top_domains_post(opts)

List domains most cited in LLM answers

Rank the domains most frequently cited as sources in LLM answers for a target domain or keyword, with per-dimension breakdowns.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::GeoApi.new
opts = {
  geo_mentions_top_domains_request: Unifapi::GeoMentionsTopDomainsRequest.new({target: [Unifapi::GeoMentionsTarget.new]}) # GeoMentionsTopDomainsRequest | 
}

begin
  # List domains most cited in LLM answers
  result = api_instance.geo_mentions_top_domains_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling GeoApi->geo_mentions_top_domains_post: #{e}"
end
```

#### Using the geo_mentions_top_domains_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GeoMentionsTopDomainsPost200Response>, Integer, Hash)> geo_mentions_top_domains_post_with_http_info(opts)

```ruby
begin
  # List domains most cited in LLM answers
  data, status_code, headers = api_instance.geo_mentions_top_domains_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GeoMentionsTopDomainsPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling GeoApi->geo_mentions_top_domains_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **geo_mentions_top_domains_request** | [**GeoMentionsTopDomainsRequest**](GeoMentionsTopDomainsRequest.md) |  | [optional] |

### Return type

[**GeoMentionsTopDomainsPost200Response**](GeoMentionsTopDomainsPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## geo_mentions_top_pages_post

> <GeoMentionsTopPagesPost200Response> geo_mentions_top_pages_post(opts)

List pages most cited in LLM answers

Rank the pages most frequently cited as sources in LLM answers for a target domain or keyword, with per-dimension breakdowns.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::GeoApi.new
opts = {
  geo_mentions_top_pages_request: Unifapi::GeoMentionsTopPagesRequest.new({target: [Unifapi::GeoMentionsTarget.new]}) # GeoMentionsTopPagesRequest | 
}

begin
  # List pages most cited in LLM answers
  result = api_instance.geo_mentions_top_pages_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling GeoApi->geo_mentions_top_pages_post: #{e}"
end
```

#### Using the geo_mentions_top_pages_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GeoMentionsTopPagesPost200Response>, Integer, Hash)> geo_mentions_top_pages_post_with_http_info(opts)

```ruby
begin
  # List pages most cited in LLM answers
  data, status_code, headers = api_instance.geo_mentions_top_pages_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GeoMentionsTopPagesPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling GeoApi->geo_mentions_top_pages_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **geo_mentions_top_pages_request** | [**GeoMentionsTopPagesRequest**](GeoMentionsTopPagesRequest.md) |  | [optional] |

### Return type

[**GeoMentionsTopPagesPost200Response**](GeoMentionsTopPagesPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## geo_serp_post

> <GeoSerpPost200Response> geo_serp_post(opts)

Search AI Mode generative results

Run one live AI Mode search for generative answer evidence, cited sources, and target-domain visibility.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::GeoApi.new
opts = {
  geo_serp_request: Unifapi::GeoSerpRequest.new({query: 'query_example'}) # GeoSerpRequest | 
}

begin
  # Search AI Mode generative results
  result = api_instance.geo_serp_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling GeoApi->geo_serp_post: #{e}"
end
```

#### Using the geo_serp_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GeoSerpPost200Response>, Integer, Hash)> geo_serp_post_with_http_info(opts)

```ruby
begin
  # Search AI Mode generative results
  data, status_code, headers = api_instance.geo_serp_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GeoSerpPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling GeoApi->geo_serp_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **geo_serp_request** | [**GeoSerpRequest**](GeoSerpRequest.md) |  | [optional] |

### Return type

[**GeoSerpPost200Response**](GeoSerpPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

