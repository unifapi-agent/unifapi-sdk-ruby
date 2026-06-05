# Unifapi::SeoApi

All URIs are relative to *https://api.unifapi.com*

| Method | HTTP request | Description |
| ------ | ------------ | ----------- |
| [**seo_backlinks_anchors_post**](SeoApi.md#seo_backlinks_anchors_post) | **POST** /seo/backlinks/anchors | Get anchor texts used in backlinks to a target |
| [**seo_backlinks_bulk_backlinks_post**](SeoApi.md#seo_backlinks_bulk_backlinks_post) | **POST** /seo/backlinks/bulk-backlinks | Count backlinks for many targets |
| [**seo_backlinks_bulk_new_lost_backlinks_post**](SeoApi.md#seo_backlinks_bulk_new_lost_backlinks_post) | **POST** /seo/backlinks/bulk-new-lost-backlinks | Count new and lost backlinks for many targets |
| [**seo_backlinks_bulk_new_lost_referring_domains_post**](SeoApi.md#seo_backlinks_bulk_new_lost_referring_domains_post) | **POST** /seo/backlinks/bulk-new-lost-referring-domains | Count new and lost referring domains for many targets |
| [**seo_backlinks_bulk_pages_summary_post**](SeoApi.md#seo_backlinks_bulk_pages_summary_post) | **POST** /seo/backlinks/bulk-pages-summary | Summarize backlinks for many pages at once |
| [**seo_backlinks_bulk_ranks_post**](SeoApi.md#seo_backlinks_bulk_ranks_post) | **POST** /seo/backlinks/bulk-ranks | Get backlink ranks for many targets |
| [**seo_backlinks_bulk_referring_domains_post**](SeoApi.md#seo_backlinks_bulk_referring_domains_post) | **POST** /seo/backlinks/bulk-referring-domains | Count referring domains for many targets |
| [**seo_backlinks_bulk_spam_score_post**](SeoApi.md#seo_backlinks_bulk_spam_score_post) | **POST** /seo/backlinks/bulk-spam-score | Get spam scores for many targets |
| [**seo_backlinks_competitors_post**](SeoApi.md#seo_backlinks_competitors_post) | **POST** /seo/backlinks/competitors | Find competitors by shared referring domains |
| [**seo_backlinks_domain_intersection_post**](SeoApi.md#seo_backlinks_domain_intersection_post) | **POST** /seo/backlinks/domain-intersection | Find domains linking to multiple targets |
| [**seo_backlinks_domain_pages_post**](SeoApi.md#seo_backlinks_domain_pages_post) | **POST** /seo/backlinks/domain-pages | List target pages ranked by backlinks |
| [**seo_backlinks_domain_pages_summary_post**](SeoApi.md#seo_backlinks_domain_pages_summary_post) | **POST** /seo/backlinks/domain-pages-summary | Summarize backlinks for each page of a target |
| [**seo_backlinks_history_post**](SeoApi.md#seo_backlinks_history_post) | **POST** /seo/backlinks/history | Get historical backlink metrics for a target |
| [**seo_backlinks_list_post**](SeoApi.md#seo_backlinks_list_post) | **POST** /seo/backlinks/list | List individual backlinks pointing to a target |
| [**seo_backlinks_page_intersection_post**](SeoApi.md#seo_backlinks_page_intersection_post) | **POST** /seo/backlinks/page-intersection | Find pages linking to multiple targets |
| [**seo_backlinks_referring_domains_post**](SeoApi.md#seo_backlinks_referring_domains_post) | **POST** /seo/backlinks/referring-domains | List referring domains pointing to a target |
| [**seo_backlinks_referring_networks_post**](SeoApi.md#seo_backlinks_referring_networks_post) | **POST** /seo/backlinks/referring-networks | List referring IP networks pointing to a target |
| [**seo_backlinks_summary_post**](SeoApi.md#seo_backlinks_summary_post) | **POST** /seo/backlinks/summary | Get the backlink profile summary for a target |
| [**seo_backlinks_timeseries_new_lost_post**](SeoApi.md#seo_backlinks_timeseries_new_lost_post) | **POST** /seo/backlinks/timeseries-new-lost | Get new and lost backlinks over time |
| [**seo_backlinks_timeseries_post**](SeoApi.md#seo_backlinks_timeseries_post) | **POST** /seo/backlinks/timeseries | Get backlink metrics over time |
| [**seo_competitors_bulk_traffic_post**](SeoApi.md#seo_competitors_bulk_traffic_post) | **POST** /seo/competitors/bulk-traffic | Estimate organic traffic for domains |
| [**seo_competitors_domain_intersection_post**](SeoApi.md#seo_competitors_domain_intersection_post) | **POST** /seo/competitors/domain-intersection | Find keywords two domains both rank for |
| [**seo_competitors_domain_post**](SeoApi.md#seo_competitors_domain_post) | **POST** /seo/competitors/domain | Find a domain&#39;s organic competitors |
| [**seo_competitors_domain_rank_overview_post**](SeoApi.md#seo_competitors_domain_rank_overview_post) | **POST** /seo/competitors/domain-rank-overview | Get a domain&#39;s ranking and traffic overview |
| [**seo_competitors_historical_bulk_traffic_post**](SeoApi.md#seo_competitors_historical_bulk_traffic_post) | **POST** /seo/competitors/historical-bulk-traffic | Estimate historical traffic for domains |
| [**seo_competitors_historical_rank_overview_post**](SeoApi.md#seo_competitors_historical_rank_overview_post) | **POST** /seo/competitors/historical-rank-overview | Get a domain&#39;s historical ranking overview |
| [**seo_competitors_historical_serps_post**](SeoApi.md#seo_competitors_historical_serps_post) | **POST** /seo/competitors/historical-serps | Get historical SERP snapshots for a keyword |
| [**seo_competitors_page_intersection_post**](SeoApi.md#seo_competitors_page_intersection_post) | **POST** /seo/competitors/page-intersection | Find keywords specific pages rank for |
| [**seo_competitors_ranked_keywords_post**](SeoApi.md#seo_competitors_ranked_keywords_post) | **POST** /seo/competitors/ranked-keywords | Find the keywords a domain ranks for |
| [**seo_competitors_relevant_pages_post**](SeoApi.md#seo_competitors_relevant_pages_post) | **POST** /seo/competitors/relevant-pages | List a domain&#39;s top ranking pages |
| [**seo_competitors_serp_post**](SeoApi.md#seo_competitors_serp_post) | **POST** /seo/competitors/serp | Find domains competing for keywords |
| [**seo_competitors_subdomains_post**](SeoApi.md#seo_competitors_subdomains_post) | **POST** /seo/competitors/subdomains | List a domain&#39;s subdomains with traffic |
| [**seo_keywords_autocomplete_post**](SeoApi.md#seo_keywords_autocomplete_post) | **POST** /seo/keywords/autocomplete | Collect autocomplete keyword suggestions |
| [**seo_keywords_difficulty_post**](SeoApi.md#seo_keywords_difficulty_post) | **POST** /seo/keywords/difficulty | Score keyword difficulty |
| [**seo_keywords_for_site_post**](SeoApi.md#seo_keywords_for_site_post) | **POST** /seo/keywords/for-site | Find keywords a domain ranks for |
| [**seo_keywords_history_post**](SeoApi.md#seo_keywords_history_post) | **POST** /seo/keywords/history | Get historical keyword data |
| [**seo_keywords_ideas_post**](SeoApi.md#seo_keywords_ideas_post) | **POST** /seo/keywords/ideas | Discover keyword ideas |
| [**seo_keywords_intent_post**](SeoApi.md#seo_keywords_intent_post) | **POST** /seo/keywords/intent | Classify keyword search intent |
| [**seo_keywords_overview_post**](SeoApi.md#seo_keywords_overview_post) | **POST** /seo/keywords/overview | Look up keyword metrics |
| [**seo_keywords_related_post**](SeoApi.md#seo_keywords_related_post) | **POST** /seo/keywords/related | Find related keywords |
| [**seo_keywords_suggestions_post**](SeoApi.md#seo_keywords_suggestions_post) | **POST** /seo/keywords/suggestions | Find keyword suggestions |
| [**seo_serp_post**](SeoApi.md#seo_serp_post) | **POST** /seo/serp | Collect organic SERP SEO evidence |


## seo_backlinks_anchors_post

> <SeoBacklinksAnchorsPost200Response> seo_backlinks_anchors_post(opts)

Get anchor texts used in backlinks to a target

Return the anchor texts used in backlinks pointing to a target, each with backlink, referring-domain, and spam-score counters, to analyze anchor-text distribution.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_backlinks_anchors_request: Unifapi::SeoBacklinksAnchorsRequest.new({target: 'target_example'}) # SeoBacklinksAnchorsRequest | 
}

begin
  # Get anchor texts used in backlinks to a target
  result = api_instance.seo_backlinks_anchors_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_anchors_post: #{e}"
end
```

#### Using the seo_backlinks_anchors_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoBacklinksAnchorsPost200Response>, Integer, Hash)> seo_backlinks_anchors_post_with_http_info(opts)

```ruby
begin
  # Get anchor texts used in backlinks to a target
  data, status_code, headers = api_instance.seo_backlinks_anchors_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoBacklinksAnchorsPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_anchors_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_backlinks_anchors_request** | [**SeoBacklinksAnchorsRequest**](SeoBacklinksAnchorsRequest.md) |  | [optional] |

### Return type

[**SeoBacklinksAnchorsPost200Response**](SeoBacklinksAnchorsPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_backlinks_bulk_backlinks_post

> <SeoBacklinksBulkBacklinksPost200Response> seo_backlinks_bulk_backlinks_post(opts)

Count backlinks for many targets

Return the total number of backlinks pointing to up to 1000 domains, subdomains, or pages at once, for bulk link-volume comparison.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_backlinks_bulk_backlinks_request: Unifapi::SeoBacklinksBulkBacklinksRequest.new({targets: ['targets_example']}) # SeoBacklinksBulkBacklinksRequest | 
}

begin
  # Count backlinks for many targets
  result = api_instance.seo_backlinks_bulk_backlinks_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_bulk_backlinks_post: #{e}"
end
```

#### Using the seo_backlinks_bulk_backlinks_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoBacklinksBulkBacklinksPost200Response>, Integer, Hash)> seo_backlinks_bulk_backlinks_post_with_http_info(opts)

```ruby
begin
  # Count backlinks for many targets
  data, status_code, headers = api_instance.seo_backlinks_bulk_backlinks_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoBacklinksBulkBacklinksPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_bulk_backlinks_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_backlinks_bulk_backlinks_request** | [**SeoBacklinksBulkBacklinksRequest**](SeoBacklinksBulkBacklinksRequest.md) |  | [optional] |

### Return type

[**SeoBacklinksBulkBacklinksPost200Response**](SeoBacklinksBulkBacklinksPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_backlinks_bulk_new_lost_backlinks_post

> <SeoBacklinksBulkNewLostBacklinksPost200Response> seo_backlinks_bulk_new_lost_backlinks_post(opts)

Count new and lost backlinks for many targets

Return the number of new and lost backlinks for up to 1000 domains, subdomains, or pages since a given date, for bulk link-velocity tracking.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_backlinks_bulk_new_lost_backlinks_request: Unifapi::SeoBacklinksBulkNewLostBacklinksRequest.new({targets: ['targets_example']}) # SeoBacklinksBulkNewLostBacklinksRequest | 
}

begin
  # Count new and lost backlinks for many targets
  result = api_instance.seo_backlinks_bulk_new_lost_backlinks_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_bulk_new_lost_backlinks_post: #{e}"
end
```

#### Using the seo_backlinks_bulk_new_lost_backlinks_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoBacklinksBulkNewLostBacklinksPost200Response>, Integer, Hash)> seo_backlinks_bulk_new_lost_backlinks_post_with_http_info(opts)

```ruby
begin
  # Count new and lost backlinks for many targets
  data, status_code, headers = api_instance.seo_backlinks_bulk_new_lost_backlinks_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoBacklinksBulkNewLostBacklinksPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_bulk_new_lost_backlinks_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_backlinks_bulk_new_lost_backlinks_request** | [**SeoBacklinksBulkNewLostBacklinksRequest**](SeoBacklinksBulkNewLostBacklinksRequest.md) |  | [optional] |

### Return type

[**SeoBacklinksBulkNewLostBacklinksPost200Response**](SeoBacklinksBulkNewLostBacklinksPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_backlinks_bulk_new_lost_referring_domains_post

> <SeoBacklinksBulkNewLostReferringDomainsPost200Response> seo_backlinks_bulk_new_lost_referring_domains_post(opts)

Count new and lost referring domains for many targets

Return the number of new and lost referring domains for up to 1000 domains, subdomains, or pages since a given date, for bulk referring-domain velocity tracking.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_backlinks_bulk_new_lost_referring_domains_request: Unifapi::SeoBacklinksBulkNewLostReferringDomainsRequest.new({targets: ['targets_example']}) # SeoBacklinksBulkNewLostReferringDomainsRequest | 
}

begin
  # Count new and lost referring domains for many targets
  result = api_instance.seo_backlinks_bulk_new_lost_referring_domains_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_bulk_new_lost_referring_domains_post: #{e}"
end
```

#### Using the seo_backlinks_bulk_new_lost_referring_domains_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoBacklinksBulkNewLostReferringDomainsPost200Response>, Integer, Hash)> seo_backlinks_bulk_new_lost_referring_domains_post_with_http_info(opts)

```ruby
begin
  # Count new and lost referring domains for many targets
  data, status_code, headers = api_instance.seo_backlinks_bulk_new_lost_referring_domains_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoBacklinksBulkNewLostReferringDomainsPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_bulk_new_lost_referring_domains_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_backlinks_bulk_new_lost_referring_domains_request** | [**SeoBacklinksBulkNewLostReferringDomainsRequest**](SeoBacklinksBulkNewLostReferringDomainsRequest.md) |  | [optional] |

### Return type

[**SeoBacklinksBulkNewLostReferringDomainsPost200Response**](SeoBacklinksBulkNewLostReferringDomainsPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_backlinks_bulk_pages_summary_post

> <SeoBacklinksBulkPagesSummaryPost200Response> seo_backlinks_bulk_pages_summary_post(opts)

Summarize backlinks for many pages at once

Return backlink summaries for up to 1000 pages, domains, or subdomains at once, each with backlink, referring-domain, and spam-score counters, for bulk link-profile comparison.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_backlinks_bulk_pages_summary_request: Unifapi::SeoBacklinksBulkPagesSummaryRequest.new({targets: ['targets_example']}) # SeoBacklinksBulkPagesSummaryRequest | 
}

begin
  # Summarize backlinks for many pages at once
  result = api_instance.seo_backlinks_bulk_pages_summary_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_bulk_pages_summary_post: #{e}"
end
```

#### Using the seo_backlinks_bulk_pages_summary_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoBacklinksBulkPagesSummaryPost200Response>, Integer, Hash)> seo_backlinks_bulk_pages_summary_post_with_http_info(opts)

```ruby
begin
  # Summarize backlinks for many pages at once
  data, status_code, headers = api_instance.seo_backlinks_bulk_pages_summary_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoBacklinksBulkPagesSummaryPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_bulk_pages_summary_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_backlinks_bulk_pages_summary_request** | [**SeoBacklinksBulkPagesSummaryRequest**](SeoBacklinksBulkPagesSummaryRequest.md) |  | [optional] |

### Return type

[**SeoBacklinksBulkPagesSummaryPost200Response**](SeoBacklinksBulkPagesSummaryPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_backlinks_bulk_ranks_post

> <SeoBacklinksBulkRanksPost200Response> seo_backlinks_bulk_ranks_post(opts)

Get backlink ranks for many targets

Return the backlink rank score (0-1000, similar to PageRank) for up to 1000 domains, subdomains, or pages at once, for quick bulk authority comparison.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_backlinks_bulk_ranks_request: Unifapi::SeoBacklinksBulkRanksRequest.new({targets: ['targets_example']}) # SeoBacklinksBulkRanksRequest | 
}

begin
  # Get backlink ranks for many targets
  result = api_instance.seo_backlinks_bulk_ranks_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_bulk_ranks_post: #{e}"
end
```

#### Using the seo_backlinks_bulk_ranks_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoBacklinksBulkRanksPost200Response>, Integer, Hash)> seo_backlinks_bulk_ranks_post_with_http_info(opts)

```ruby
begin
  # Get backlink ranks for many targets
  data, status_code, headers = api_instance.seo_backlinks_bulk_ranks_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoBacklinksBulkRanksPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_bulk_ranks_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_backlinks_bulk_ranks_request** | [**SeoBacklinksBulkRanksRequest**](SeoBacklinksBulkRanksRequest.md) |  | [optional] |

### Return type

[**SeoBacklinksBulkRanksPost200Response**](SeoBacklinksBulkRanksPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_backlinks_bulk_referring_domains_post

> <SeoBacklinksBulkReferringDomainsPost200Response> seo_backlinks_bulk_referring_domains_post(opts)

Count referring domains for many targets

Return the number of referring domains pointing to up to 1000 domains, subdomains, or pages at once, for bulk referring-domain comparison.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_backlinks_bulk_referring_domains_request: Unifapi::SeoBacklinksBulkReferringDomainsRequest.new({targets: ['targets_example']}) # SeoBacklinksBulkReferringDomainsRequest | 
}

begin
  # Count referring domains for many targets
  result = api_instance.seo_backlinks_bulk_referring_domains_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_bulk_referring_domains_post: #{e}"
end
```

#### Using the seo_backlinks_bulk_referring_domains_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoBacklinksBulkReferringDomainsPost200Response>, Integer, Hash)> seo_backlinks_bulk_referring_domains_post_with_http_info(opts)

```ruby
begin
  # Count referring domains for many targets
  data, status_code, headers = api_instance.seo_backlinks_bulk_referring_domains_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoBacklinksBulkReferringDomainsPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_bulk_referring_domains_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_backlinks_bulk_referring_domains_request** | [**SeoBacklinksBulkReferringDomainsRequest**](SeoBacklinksBulkReferringDomainsRequest.md) |  | [optional] |

### Return type

[**SeoBacklinksBulkReferringDomainsPost200Response**](SeoBacklinksBulkReferringDomainsPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_backlinks_bulk_spam_score_post

> <SeoBacklinksBulkSpamScorePost200Response> seo_backlinks_bulk_spam_score_post(opts)

Get spam scores for many targets

Return the DataForSEO spam score (0-100) for up to 1000 domains, subdomains, or pages at once, to flag risky backlink targets in bulk.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_backlinks_bulk_spam_score_request: Unifapi::SeoBacklinksBulkSpamScoreRequest.new({targets: ['targets_example']}) # SeoBacklinksBulkSpamScoreRequest | 
}

begin
  # Get spam scores for many targets
  result = api_instance.seo_backlinks_bulk_spam_score_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_bulk_spam_score_post: #{e}"
end
```

#### Using the seo_backlinks_bulk_spam_score_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoBacklinksBulkSpamScorePost200Response>, Integer, Hash)> seo_backlinks_bulk_spam_score_post_with_http_info(opts)

```ruby
begin
  # Get spam scores for many targets
  data, status_code, headers = api_instance.seo_backlinks_bulk_spam_score_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoBacklinksBulkSpamScorePost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_bulk_spam_score_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_backlinks_bulk_spam_score_request** | [**SeoBacklinksBulkSpamScoreRequest**](SeoBacklinksBulkSpamScoreRequest.md) |  | [optional] |

### Return type

[**SeoBacklinksBulkSpamScorePost200Response**](SeoBacklinksBulkSpamScorePost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_backlinks_competitors_post

> <SeoBacklinksCompetitorsPost200Response> seo_backlinks_competitors_post(opts)

Find competitors by shared referring domains

Return the domains that share referring domains with a target, ranked by the number of shared referring domains, to discover competitors in the same backlink neighborhood.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_backlinks_competitors_request: Unifapi::SeoBacklinksCompetitorsRequest.new({target: 'target_example'}) # SeoBacklinksCompetitorsRequest | 
}

begin
  # Find competitors by shared referring domains
  result = api_instance.seo_backlinks_competitors_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_competitors_post: #{e}"
end
```

#### Using the seo_backlinks_competitors_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoBacklinksCompetitorsPost200Response>, Integer, Hash)> seo_backlinks_competitors_post_with_http_info(opts)

```ruby
begin
  # Find competitors by shared referring domains
  data, status_code, headers = api_instance.seo_backlinks_competitors_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoBacklinksCompetitorsPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_competitors_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_backlinks_competitors_request** | [**SeoBacklinksCompetitorsRequest**](SeoBacklinksCompetitorsRequest.md) |  | [optional] |

### Return type

[**SeoBacklinksCompetitorsPost200Response**](SeoBacklinksCompetitorsPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_backlinks_domain_intersection_post

> <SeoBacklinksDomainIntersectionPost200Response> seo_backlinks_domain_intersection_post(opts)

Find domains linking to multiple targets

Return the domains that link to a set of targets, with per-target backlink metrics. Useful for a link-gap analysis: domains linking to competitors but not to your site.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_backlinks_domain_intersection_request: Unifapi::SeoBacklinksDomainIntersectionRequest.new({targets: ['targets_example']}) # SeoBacklinksDomainIntersectionRequest | 
}

begin
  # Find domains linking to multiple targets
  result = api_instance.seo_backlinks_domain_intersection_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_domain_intersection_post: #{e}"
end
```

#### Using the seo_backlinks_domain_intersection_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoBacklinksDomainIntersectionPost200Response>, Integer, Hash)> seo_backlinks_domain_intersection_post_with_http_info(opts)

```ruby
begin
  # Find domains linking to multiple targets
  data, status_code, headers = api_instance.seo_backlinks_domain_intersection_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoBacklinksDomainIntersectionPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_domain_intersection_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_backlinks_domain_intersection_request** | [**SeoBacklinksDomainIntersectionRequest**](SeoBacklinksDomainIntersectionRequest.md) |  | [optional] |

### Return type

[**SeoBacklinksDomainIntersectionPost200Response**](SeoBacklinksDomainIntersectionPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_backlinks_domain_pages_post

> <SeoBacklinksDomainPagesPost200Response> seo_backlinks_domain_pages_post(opts)

List target pages ranked by backlinks

Return the pages of a target domain or subdomain that receive backlinks, each with crawl data and backlink counters, to find the most-linked pages of a site.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_backlinks_domain_pages_request: Unifapi::SeoBacklinksDomainPagesRequest.new({target: 'target_example'}) # SeoBacklinksDomainPagesRequest | 
}

begin
  # List target pages ranked by backlinks
  result = api_instance.seo_backlinks_domain_pages_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_domain_pages_post: #{e}"
end
```

#### Using the seo_backlinks_domain_pages_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoBacklinksDomainPagesPost200Response>, Integer, Hash)> seo_backlinks_domain_pages_post_with_http_info(opts)

```ruby
begin
  # List target pages ranked by backlinks
  data, status_code, headers = api_instance.seo_backlinks_domain_pages_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoBacklinksDomainPagesPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_domain_pages_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_backlinks_domain_pages_request** | [**SeoBacklinksDomainPagesRequest**](SeoBacklinksDomainPagesRequest.md) |  | [optional] |

### Return type

[**SeoBacklinksDomainPagesPost200Response**](SeoBacklinksDomainPagesPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_backlinks_domain_pages_summary_post

> <SeoBacklinksDomainPagesSummaryPost200Response> seo_backlinks_domain_pages_summary_post(opts)

Summarize backlinks for each page of a target

Return per-page backlink summaries for a target domain or subdomain, each page with backlink, referring-domain, and spam-score counters, to find the most-linked pages.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_backlinks_domain_pages_summary_request: Unifapi::SeoBacklinksDomainPagesSummaryRequest.new({target: 'target_example'}) # SeoBacklinksDomainPagesSummaryRequest | 
}

begin
  # Summarize backlinks for each page of a target
  result = api_instance.seo_backlinks_domain_pages_summary_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_domain_pages_summary_post: #{e}"
end
```

#### Using the seo_backlinks_domain_pages_summary_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoBacklinksDomainPagesSummaryPost200Response>, Integer, Hash)> seo_backlinks_domain_pages_summary_post_with_http_info(opts)

```ruby
begin
  # Summarize backlinks for each page of a target
  data, status_code, headers = api_instance.seo_backlinks_domain_pages_summary_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoBacklinksDomainPagesSummaryPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_domain_pages_summary_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_backlinks_domain_pages_summary_request** | [**SeoBacklinksDomainPagesSummaryRequest**](SeoBacklinksDomainPagesSummaryRequest.md) |  | [optional] |

### Return type

[**SeoBacklinksDomainPagesSummaryPost200Response**](SeoBacklinksDomainPagesSummaryPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_backlinks_history_post

> <SeoBacklinksHistoryPost200Response> seo_backlinks_history_post(opts)

Get historical backlink metrics for a target

Return a monthly time series of a target's backlink profile since 2019 — backlinks, referring domains, new/lost counts, and rank — for link-growth trend analysis.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_backlinks_history_request: Unifapi::SeoBacklinksHistoryRequest.new({target: 'target_example'}) # SeoBacklinksHistoryRequest | 
}

begin
  # Get historical backlink metrics for a target
  result = api_instance.seo_backlinks_history_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_history_post: #{e}"
end
```

#### Using the seo_backlinks_history_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoBacklinksHistoryPost200Response>, Integer, Hash)> seo_backlinks_history_post_with_http_info(opts)

```ruby
begin
  # Get historical backlink metrics for a target
  data, status_code, headers = api_instance.seo_backlinks_history_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoBacklinksHistoryPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_history_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_backlinks_history_request** | [**SeoBacklinksHistoryRequest**](SeoBacklinksHistoryRequest.md) |  | [optional] |

### Return type

[**SeoBacklinksHistoryPost200Response**](SeoBacklinksHistoryPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_backlinks_list_post

> <SeoBacklinksListPost200Response> seo_backlinks_list_post(opts)

List individual backlinks pointing to a target

Return the individual backlinks pointing to a target domain, subdomain, or page, each with the referring URL, anchor, dofollow flag, rank, and spam score, for detailed link auditing.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_backlinks_list_request: Unifapi::SeoBacklinksListRequest.new({target: 'target_example'}) # SeoBacklinksListRequest | 
}

begin
  # List individual backlinks pointing to a target
  result = api_instance.seo_backlinks_list_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_list_post: #{e}"
end
```

#### Using the seo_backlinks_list_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoBacklinksListPost200Response>, Integer, Hash)> seo_backlinks_list_post_with_http_info(opts)

```ruby
begin
  # List individual backlinks pointing to a target
  data, status_code, headers = api_instance.seo_backlinks_list_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoBacklinksListPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_list_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_backlinks_list_request** | [**SeoBacklinksListRequest**](SeoBacklinksListRequest.md) |  | [optional] |

### Return type

[**SeoBacklinksListPost200Response**](SeoBacklinksListPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_backlinks_page_intersection_post

> <SeoBacklinksPageIntersectionPost200Response> seo_backlinks_page_intersection_post(opts)

Find pages linking to multiple targets

Return the referring pages that link to a set of targets, with the backlinks to each target. Useful for finding pages that link to your competitors but not to your site.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_backlinks_page_intersection_request: Unifapi::SeoBacklinksPageIntersectionRequest.new({targets: ['targets_example']}) # SeoBacklinksPageIntersectionRequest | 
}

begin
  # Find pages linking to multiple targets
  result = api_instance.seo_backlinks_page_intersection_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_page_intersection_post: #{e}"
end
```

#### Using the seo_backlinks_page_intersection_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoBacklinksPageIntersectionPost200Response>, Integer, Hash)> seo_backlinks_page_intersection_post_with_http_info(opts)

```ruby
begin
  # Find pages linking to multiple targets
  data, status_code, headers = api_instance.seo_backlinks_page_intersection_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoBacklinksPageIntersectionPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_page_intersection_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_backlinks_page_intersection_request** | [**SeoBacklinksPageIntersectionRequest**](SeoBacklinksPageIntersectionRequest.md) |  | [optional] |

### Return type

[**SeoBacklinksPageIntersectionPost200Response**](SeoBacklinksPageIntersectionPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_backlinks_referring_domains_post

> <SeoBacklinksReferringDomainsPost200Response> seo_backlinks_referring_domains_post(opts)

List referring domains pointing to a target

Return the domains that link to a target domain, subdomain, or page, each with backlink, referring-domain, and spam-score counters for referring-domain analysis.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_referring_domains_request: Unifapi::SeoReferringDomainsRequest.new({target: 'target_example'}) # SeoReferringDomainsRequest | 
}

begin
  # List referring domains pointing to a target
  result = api_instance.seo_backlinks_referring_domains_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_referring_domains_post: #{e}"
end
```

#### Using the seo_backlinks_referring_domains_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoBacklinksReferringDomainsPost200Response>, Integer, Hash)> seo_backlinks_referring_domains_post_with_http_info(opts)

```ruby
begin
  # List referring domains pointing to a target
  data, status_code, headers = api_instance.seo_backlinks_referring_domains_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoBacklinksReferringDomainsPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_referring_domains_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_referring_domains_request** | [**SeoReferringDomainsRequest**](SeoReferringDomainsRequest.md) |  | [optional] |

### Return type

[**SeoBacklinksReferringDomainsPost200Response**](SeoBacklinksReferringDomainsPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_backlinks_referring_networks_post

> <SeoBacklinksReferringNetworksPost200Response> seo_backlinks_referring_networks_post(opts)

List referring IP networks pointing to a target

Return the IP addresses or subnets that host pages linking to a target, each with backlink and referring-domain counters, to assess referring-network diversity.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_backlinks_referring_networks_request: Unifapi::SeoBacklinksReferringNetworksRequest.new({target: 'target_example'}) # SeoBacklinksReferringNetworksRequest | 
}

begin
  # List referring IP networks pointing to a target
  result = api_instance.seo_backlinks_referring_networks_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_referring_networks_post: #{e}"
end
```

#### Using the seo_backlinks_referring_networks_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoBacklinksReferringNetworksPost200Response>, Integer, Hash)> seo_backlinks_referring_networks_post_with_http_info(opts)

```ruby
begin
  # List referring IP networks pointing to a target
  data, status_code, headers = api_instance.seo_backlinks_referring_networks_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoBacklinksReferringNetworksPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_referring_networks_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_backlinks_referring_networks_request** | [**SeoBacklinksReferringNetworksRequest**](SeoBacklinksReferringNetworksRequest.md) |  | [optional] |

### Return type

[**SeoBacklinksReferringNetworksPost200Response**](SeoBacklinksReferringNetworksPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_backlinks_summary_post

> <SeoBacklinksSummaryPost200Response> seo_backlinks_summary_post(opts)

Get the backlink profile summary for a target

Return an overview of a target's backlink profile: total backlinks, referring domains/pages/IPs, rank, spam score, and broken-link counters, for a quick link-profile health check.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_backlinks_summary_request: Unifapi::SeoBacklinksSummaryRequest.new({target: 'target_example'}) # SeoBacklinksSummaryRequest | 
}

begin
  # Get the backlink profile summary for a target
  result = api_instance.seo_backlinks_summary_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_summary_post: #{e}"
end
```

#### Using the seo_backlinks_summary_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoBacklinksSummaryPost200Response>, Integer, Hash)> seo_backlinks_summary_post_with_http_info(opts)

```ruby
begin
  # Get the backlink profile summary for a target
  data, status_code, headers = api_instance.seo_backlinks_summary_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoBacklinksSummaryPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_summary_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_backlinks_summary_request** | [**SeoBacklinksSummaryRequest**](SeoBacklinksSummaryRequest.md) |  | [optional] |

### Return type

[**SeoBacklinksSummaryPost200Response**](SeoBacklinksSummaryPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_backlinks_timeseries_new_lost_post

> <SeoBacklinksTimeseriesNewLostPost200Response> seo_backlinks_timeseries_new_lost_post(opts)

Get new and lost backlinks over time

Return a time series of new and lost backlinks and referring domains for a target, grouped by day, week, month, or year, for link-velocity analysis.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_backlinks_timeseries_new_lost_request: Unifapi::SeoBacklinksTimeseriesNewLostRequest.new({target: 'target_example'}) # SeoBacklinksTimeseriesNewLostRequest | 
}

begin
  # Get new and lost backlinks over time
  result = api_instance.seo_backlinks_timeseries_new_lost_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_timeseries_new_lost_post: #{e}"
end
```

#### Using the seo_backlinks_timeseries_new_lost_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoBacklinksTimeseriesNewLostPost200Response>, Integer, Hash)> seo_backlinks_timeseries_new_lost_post_with_http_info(opts)

```ruby
begin
  # Get new and lost backlinks over time
  data, status_code, headers = api_instance.seo_backlinks_timeseries_new_lost_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoBacklinksTimeseriesNewLostPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_timeseries_new_lost_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_backlinks_timeseries_new_lost_request** | [**SeoBacklinksTimeseriesNewLostRequest**](SeoBacklinksTimeseriesNewLostRequest.md) |  | [optional] |

### Return type

[**SeoBacklinksTimeseriesNewLostPost200Response**](SeoBacklinksTimeseriesNewLostPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_backlinks_timeseries_post

> <SeoBacklinksTimeseriesPost200Response> seo_backlinks_timeseries_post(opts)

Get backlink metrics over time

Return a time series of a target's backlink metrics grouped by day, week, month, or year between two dates, for tracking backlink and referring-domain trends.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_backlinks_timeseries_request: Unifapi::SeoBacklinksTimeseriesRequest.new({target: 'target_example'}) # SeoBacklinksTimeseriesRequest | 
}

begin
  # Get backlink metrics over time
  result = api_instance.seo_backlinks_timeseries_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_timeseries_post: #{e}"
end
```

#### Using the seo_backlinks_timeseries_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoBacklinksTimeseriesPost200Response>, Integer, Hash)> seo_backlinks_timeseries_post_with_http_info(opts)

```ruby
begin
  # Get backlink metrics over time
  data, status_code, headers = api_instance.seo_backlinks_timeseries_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoBacklinksTimeseriesPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_backlinks_timeseries_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_backlinks_timeseries_request** | [**SeoBacklinksTimeseriesRequest**](SeoBacklinksTimeseriesRequest.md) |  | [optional] |

### Return type

[**SeoBacklinksTimeseriesPost200Response**](SeoBacklinksTimeseriesPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_competitors_bulk_traffic_post

> <SeoCompetitorsBulkTrafficPost200Response> seo_competitors_bulk_traffic_post(opts)

Estimate organic traffic for domains

Return the estimated monthly organic and paid search traffic for a list of domains, for quick competitor sizing and prospecting across many domains at once.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_bulk_traffic_request: Unifapi::SeoBulkTrafficRequest.new({targets: ['targets_example']}) # SeoBulkTrafficRequest | 
}

begin
  # Estimate organic traffic for domains
  result = api_instance.seo_competitors_bulk_traffic_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_competitors_bulk_traffic_post: #{e}"
end
```

#### Using the seo_competitors_bulk_traffic_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoCompetitorsBulkTrafficPost200Response>, Integer, Hash)> seo_competitors_bulk_traffic_post_with_http_info(opts)

```ruby
begin
  # Estimate organic traffic for domains
  data, status_code, headers = api_instance.seo_competitors_bulk_traffic_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoCompetitorsBulkTrafficPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_competitors_bulk_traffic_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_bulk_traffic_request** | [**SeoBulkTrafficRequest**](SeoBulkTrafficRequest.md) |  | [optional] |

### Return type

[**SeoCompetitorsBulkTrafficPost200Response**](SeoCompetitorsBulkTrafficPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_competitors_domain_intersection_post

> <SeoCompetitorsDomainIntersectionPost200Response> seo_competitors_domain_intersection_post(opts)

Find keywords two domains both rank for

Return the keywords for which two domains both rank, with each domain's position and URL, to find shared keywords or keyword gaps between competitors.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_domain_intersection_request: Unifapi::SeoDomainIntersectionRequest.new({target1: 'target1_example', target2: 'target2_example'}) # SeoDomainIntersectionRequest | 
}

begin
  # Find keywords two domains both rank for
  result = api_instance.seo_competitors_domain_intersection_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_competitors_domain_intersection_post: #{e}"
end
```

#### Using the seo_competitors_domain_intersection_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoCompetitorsDomainIntersectionPost200Response>, Integer, Hash)> seo_competitors_domain_intersection_post_with_http_info(opts)

```ruby
begin
  # Find keywords two domains both rank for
  data, status_code, headers = api_instance.seo_competitors_domain_intersection_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoCompetitorsDomainIntersectionPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_competitors_domain_intersection_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_domain_intersection_request** | [**SeoDomainIntersectionRequest**](SeoDomainIntersectionRequest.md) |  | [optional] |

### Return type

[**SeoCompetitorsDomainIntersectionPost200Response**](SeoCompetitorsDomainIntersectionPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_competitors_domain_post

> <SeoCompetitorsDomainPost200Response> seo_competitors_domain_post(opts)

Find a domain's organic competitors

Return the domains that compete with a target domain in organic search, with shared-keyword counts and ranking/traffic metrics, for competitive landscape analysis.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_competitors_domain_request: Unifapi::SeoCompetitorsDomainRequest.new({target: 'target_example'}) # SeoCompetitorsDomainRequest | 
}

begin
  # Find a domain's organic competitors
  result = api_instance.seo_competitors_domain_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_competitors_domain_post: #{e}"
end
```

#### Using the seo_competitors_domain_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoCompetitorsDomainPost200Response>, Integer, Hash)> seo_competitors_domain_post_with_http_info(opts)

```ruby
begin
  # Find a domain's organic competitors
  data, status_code, headers = api_instance.seo_competitors_domain_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoCompetitorsDomainPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_competitors_domain_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_competitors_domain_request** | [**SeoCompetitorsDomainRequest**](SeoCompetitorsDomainRequest.md) |  | [optional] |

### Return type

[**SeoCompetitorsDomainPost200Response**](SeoCompetitorsDomainPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_competitors_domain_rank_overview_post

> <SeoCompetitorsDomainRankOverviewPost200Response> seo_competitors_domain_rank_overview_post(opts)

Get a domain's ranking and traffic overview

Return the organic and paid ranking distribution and estimated traffic for a target domain, summarizing how many keywords it ranks for in each position bucket.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_domain_rank_overview_request: Unifapi::SeoDomainRankOverviewRequest.new({target: 'target_example'}) # SeoDomainRankOverviewRequest | 
}

begin
  # Get a domain's ranking and traffic overview
  result = api_instance.seo_competitors_domain_rank_overview_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_competitors_domain_rank_overview_post: #{e}"
end
```

#### Using the seo_competitors_domain_rank_overview_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoCompetitorsDomainRankOverviewPost200Response>, Integer, Hash)> seo_competitors_domain_rank_overview_post_with_http_info(opts)

```ruby
begin
  # Get a domain's ranking and traffic overview
  data, status_code, headers = api_instance.seo_competitors_domain_rank_overview_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoCompetitorsDomainRankOverviewPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_competitors_domain_rank_overview_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_domain_rank_overview_request** | [**SeoDomainRankOverviewRequest**](SeoDomainRankOverviewRequest.md) |  | [optional] |

### Return type

[**SeoCompetitorsDomainRankOverviewPost200Response**](SeoCompetitorsDomainRankOverviewPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_competitors_historical_bulk_traffic_post

> <SeoCompetitorsHistoricalBulkTrafficPost200Response> seo_competitors_historical_bulk_traffic_post(opts)

Estimate historical traffic for domains

Return a monthly estimated organic and paid traffic time series for a list of domains since 2019, for comparing competitor growth trajectories over time.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_historical_bulk_traffic_request: Unifapi::SeoHistoricalBulkTrafficRequest.new({targets: ['targets_example']}) # SeoHistoricalBulkTrafficRequest | 
}

begin
  # Estimate historical traffic for domains
  result = api_instance.seo_competitors_historical_bulk_traffic_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_competitors_historical_bulk_traffic_post: #{e}"
end
```

#### Using the seo_competitors_historical_bulk_traffic_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoCompetitorsHistoricalBulkTrafficPost200Response>, Integer, Hash)> seo_competitors_historical_bulk_traffic_post_with_http_info(opts)

```ruby
begin
  # Estimate historical traffic for domains
  data, status_code, headers = api_instance.seo_competitors_historical_bulk_traffic_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoCompetitorsHistoricalBulkTrafficPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_competitors_historical_bulk_traffic_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_historical_bulk_traffic_request** | [**SeoHistoricalBulkTrafficRequest**](SeoHistoricalBulkTrafficRequest.md) |  | [optional] |

### Return type

[**SeoCompetitorsHistoricalBulkTrafficPost200Response**](SeoCompetitorsHistoricalBulkTrafficPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_competitors_historical_rank_overview_post

> <SeoCompetitorsHistoricalRankOverviewPost200Response> seo_competitors_historical_rank_overview_post(opts)

Get a domain's historical ranking overview

Return a monthly time series of a domain's organic and paid ranking distribution and estimated traffic since 2019, for trend and seasonality analysis.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_historical_rank_overview_request: Unifapi::SeoHistoricalRankOverviewRequest.new({target: 'target_example'}) # SeoHistoricalRankOverviewRequest | 
}

begin
  # Get a domain's historical ranking overview
  result = api_instance.seo_competitors_historical_rank_overview_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_competitors_historical_rank_overview_post: #{e}"
end
```

#### Using the seo_competitors_historical_rank_overview_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoCompetitorsHistoricalRankOverviewPost200Response>, Integer, Hash)> seo_competitors_historical_rank_overview_post_with_http_info(opts)

```ruby
begin
  # Get a domain's historical ranking overview
  data, status_code, headers = api_instance.seo_competitors_historical_rank_overview_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoCompetitorsHistoricalRankOverviewPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_competitors_historical_rank_overview_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_historical_rank_overview_request** | [**SeoHistoricalRankOverviewRequest**](SeoHistoricalRankOverviewRequest.md) |  | [optional] |

### Return type

[**SeoCompetitorsHistoricalRankOverviewPost200Response**](SeoCompetitorsHistoricalRankOverviewPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_competitors_historical_serps_post

> <SeoCompetitorsHistoricalSerpsPost200Response> seo_competitors_historical_serps_post(opts)

Get historical SERP snapshots for a keyword

Return historical snapshots of the SERP composition for a keyword since 2019, summarizing how many results and which SERP feature types appeared over time.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_historical_serps_request: Unifapi::SeoHistoricalSerpsRequest.new({keyword: 'keyword_example'}) # SeoHistoricalSerpsRequest | 
}

begin
  # Get historical SERP snapshots for a keyword
  result = api_instance.seo_competitors_historical_serps_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_competitors_historical_serps_post: #{e}"
end
```

#### Using the seo_competitors_historical_serps_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoCompetitorsHistoricalSerpsPost200Response>, Integer, Hash)> seo_competitors_historical_serps_post_with_http_info(opts)

```ruby
begin
  # Get historical SERP snapshots for a keyword
  data, status_code, headers = api_instance.seo_competitors_historical_serps_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoCompetitorsHistoricalSerpsPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_competitors_historical_serps_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_historical_serps_request** | [**SeoHistoricalSerpsRequest**](SeoHistoricalSerpsRequest.md) |  | [optional] |

### Return type

[**SeoCompetitorsHistoricalSerpsPost200Response**](SeoCompetitorsHistoricalSerpsPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_competitors_page_intersection_post

> <SeoCompetitorsPageIntersectionPost200Response> seo_competitors_page_intersection_post(opts)

Find keywords specific pages rank for

Return the keywords that a set of specific page URLs rank for, with each page's position, to analyze keyword overlap across competing pages or your own content.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_page_intersection_request: Unifapi::SeoPageIntersectionRequest.new({pages: ['pages_example']}) # SeoPageIntersectionRequest | 
}

begin
  # Find keywords specific pages rank for
  result = api_instance.seo_competitors_page_intersection_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_competitors_page_intersection_post: #{e}"
end
```

#### Using the seo_competitors_page_intersection_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoCompetitorsPageIntersectionPost200Response>, Integer, Hash)> seo_competitors_page_intersection_post_with_http_info(opts)

```ruby
begin
  # Find keywords specific pages rank for
  data, status_code, headers = api_instance.seo_competitors_page_intersection_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoCompetitorsPageIntersectionPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_competitors_page_intersection_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_page_intersection_request** | [**SeoPageIntersectionRequest**](SeoPageIntersectionRequest.md) |  | [optional] |

### Return type

[**SeoCompetitorsPageIntersectionPost200Response**](SeoCompetitorsPageIntersectionPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_competitors_ranked_keywords_post

> <SeoCompetitorsRankedKeywordsPost200Response> seo_competitors_ranked_keywords_post(opts)

Find the keywords a domain ranks for

Return the keywords a target domain or page ranks for in organic search, each with search volume, difficulty, and the exact ranking position and URL, for competitor keyword research.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_ranked_keywords_request: Unifapi::SeoRankedKeywordsRequest.new({target: 'target_example'}) # SeoRankedKeywordsRequest | 
}

begin
  # Find the keywords a domain ranks for
  result = api_instance.seo_competitors_ranked_keywords_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_competitors_ranked_keywords_post: #{e}"
end
```

#### Using the seo_competitors_ranked_keywords_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoCompetitorsRankedKeywordsPost200Response>, Integer, Hash)> seo_competitors_ranked_keywords_post_with_http_info(opts)

```ruby
begin
  # Find the keywords a domain ranks for
  data, status_code, headers = api_instance.seo_competitors_ranked_keywords_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoCompetitorsRankedKeywordsPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_competitors_ranked_keywords_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_ranked_keywords_request** | [**SeoRankedKeywordsRequest**](SeoRankedKeywordsRequest.md) |  | [optional] |

### Return type

[**SeoCompetitorsRankedKeywordsPost200Response**](SeoCompetitorsRankedKeywordsPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_competitors_relevant_pages_post

> <SeoCompetitorsRelevantPagesPost200Response> seo_competitors_relevant_pages_post(opts)

List a domain's top ranking pages

Return the pages of a target domain that drive the most organic search traffic, each with its ranking distribution and estimated traffic, for content gap and page-level analysis.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_relevant_pages_request: Unifapi::SeoRelevantPagesRequest.new({target: 'target_example'}) # SeoRelevantPagesRequest | 
}

begin
  # List a domain's top ranking pages
  result = api_instance.seo_competitors_relevant_pages_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_competitors_relevant_pages_post: #{e}"
end
```

#### Using the seo_competitors_relevant_pages_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoCompetitorsRelevantPagesPost200Response>, Integer, Hash)> seo_competitors_relevant_pages_post_with_http_info(opts)

```ruby
begin
  # List a domain's top ranking pages
  data, status_code, headers = api_instance.seo_competitors_relevant_pages_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoCompetitorsRelevantPagesPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_competitors_relevant_pages_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_relevant_pages_request** | [**SeoRelevantPagesRequest**](SeoRelevantPagesRequest.md) |  | [optional] |

### Return type

[**SeoCompetitorsRelevantPagesPost200Response**](SeoCompetitorsRelevantPagesPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_competitors_serp_post

> <SeoCompetitorsSerpPost200Response> seo_competitors_serp_post(opts)

Find domains competing for keywords

Return the domains that rank for a set of seed keywords, ranked by visibility, with average position, estimated traffic, and the number of shared keywords, to discover SERP competitors.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_serp_competitors_request: Unifapi::SeoSerpCompetitorsRequest.new({keywords: ['keywords_example']}) # SeoSerpCompetitorsRequest | 
}

begin
  # Find domains competing for keywords
  result = api_instance.seo_competitors_serp_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_competitors_serp_post: #{e}"
end
```

#### Using the seo_competitors_serp_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoCompetitorsSerpPost200Response>, Integer, Hash)> seo_competitors_serp_post_with_http_info(opts)

```ruby
begin
  # Find domains competing for keywords
  data, status_code, headers = api_instance.seo_competitors_serp_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoCompetitorsSerpPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_competitors_serp_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_serp_competitors_request** | [**SeoSerpCompetitorsRequest**](SeoSerpCompetitorsRequest.md) |  | [optional] |

### Return type

[**SeoCompetitorsSerpPost200Response**](SeoCompetitorsSerpPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_competitors_subdomains_post

> <SeoCompetitorsSubdomainsPost200Response> seo_competitors_subdomains_post(opts)

List a domain's subdomains with traffic

Return the subdomains of a target domain, each with its organic ranking distribution and estimated traffic, to see which subdomains drive search visibility.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_subdomains_request: Unifapi::SeoSubdomainsRequest.new({target: 'target_example'}) # SeoSubdomainsRequest | 
}

begin
  # List a domain's subdomains with traffic
  result = api_instance.seo_competitors_subdomains_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_competitors_subdomains_post: #{e}"
end
```

#### Using the seo_competitors_subdomains_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoCompetitorsSubdomainsPost200Response>, Integer, Hash)> seo_competitors_subdomains_post_with_http_info(opts)

```ruby
begin
  # List a domain's subdomains with traffic
  data, status_code, headers = api_instance.seo_competitors_subdomains_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoCompetitorsSubdomainsPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_competitors_subdomains_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_subdomains_request** | [**SeoSubdomainsRequest**](SeoSubdomainsRequest.md) |  | [optional] |

### Return type

[**SeoCompetitorsSubdomainsPost200Response**](SeoCompetitorsSubdomainsPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_keywords_autocomplete_post

> <SeoKeywordsAutocompletePost200Response> seo_keywords_autocomplete_post(opts)

Collect autocomplete keyword suggestions

Run one live autocomplete lookup for a seed query and receive the suggested searches the engine offers, with relevance scores — useful for SEO keyword discovery and content-gap research.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_keyword_autocomplete_request: Unifapi::SeoKeywordAutocompleteRequest.new({keyword: 'keyword_example'}) # SeoKeywordAutocompleteRequest | 
}

begin
  # Collect autocomplete keyword suggestions
  result = api_instance.seo_keywords_autocomplete_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_keywords_autocomplete_post: #{e}"
end
```

#### Using the seo_keywords_autocomplete_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoKeywordsAutocompletePost200Response>, Integer, Hash)> seo_keywords_autocomplete_post_with_http_info(opts)

```ruby
begin
  # Collect autocomplete keyword suggestions
  data, status_code, headers = api_instance.seo_keywords_autocomplete_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoKeywordsAutocompletePost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_keywords_autocomplete_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_keyword_autocomplete_request** | [**SeoKeywordAutocompleteRequest**](SeoKeywordAutocompleteRequest.md) |  | [optional] |

### Return type

[**SeoKeywordsAutocompletePost200Response**](SeoKeywordsAutocompletePost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_keywords_difficulty_post

> <SeoKeywordsDifficultyPost200Response> seo_keywords_difficulty_post(opts)

Score keyword difficulty

Return the keyword difficulty (0-100 chance of ranking in the top-10 organic results) for up to 1,000 keywords in one request, for prioritizing achievable SEO targets.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_keyword_difficulty_request: Unifapi::SeoKeywordDifficultyRequest.new({keywords: ['keywords_example']}) # SeoKeywordDifficultyRequest | 
}

begin
  # Score keyword difficulty
  result = api_instance.seo_keywords_difficulty_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_keywords_difficulty_post: #{e}"
end
```

#### Using the seo_keywords_difficulty_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoKeywordsDifficultyPost200Response>, Integer, Hash)> seo_keywords_difficulty_post_with_http_info(opts)

```ruby
begin
  # Score keyword difficulty
  data, status_code, headers = api_instance.seo_keywords_difficulty_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoKeywordsDifficultyPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_keywords_difficulty_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_keyword_difficulty_request** | [**SeoKeywordDifficultyRequest**](SeoKeywordDifficultyRequest.md) |  | [optional] |

### Return type

[**SeoKeywordsDifficultyPost200Response**](SeoKeywordsDifficultyPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_keywords_for_site_post

> <SeoKeywordsForSitePost200Response> seo_keywords_for_site_post(opts)

Find keywords a domain ranks for

Return the keywords a target domain is relevant for, each with search volume, CPC, competition, keyword difficulty, and search intent, for competitor and own-site keyword research.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_keywords_for_site_request: Unifapi::SeoKeywordsForSiteRequest.new({target: 'target_example'}) # SeoKeywordsForSiteRequest | 
}

begin
  # Find keywords a domain ranks for
  result = api_instance.seo_keywords_for_site_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_keywords_for_site_post: #{e}"
end
```

#### Using the seo_keywords_for_site_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoKeywordsForSitePost200Response>, Integer, Hash)> seo_keywords_for_site_post_with_http_info(opts)

```ruby
begin
  # Find keywords a domain ranks for
  data, status_code, headers = api_instance.seo_keywords_for_site_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoKeywordsForSitePost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_keywords_for_site_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_keywords_for_site_request** | [**SeoKeywordsForSiteRequest**](SeoKeywordsForSiteRequest.md) |  | [optional] |

### Return type

[**SeoKeywordsForSitePost200Response**](SeoKeywordsForSitePost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_keywords_history_post

> <SeoKeywordsHistoryPost200Response> seo_keywords_history_post(opts)

Get historical keyword data

Return historical search volume and search ad metrics since 2019 for specified keywords, for trend and seasonality analysis.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_keyword_history_request: Unifapi::SeoKeywordHistoryRequest.new({keywords: ['keywords_example']}) # SeoKeywordHistoryRequest | 
}

begin
  # Get historical keyword data
  result = api_instance.seo_keywords_history_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_keywords_history_post: #{e}"
end
```

#### Using the seo_keywords_history_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoKeywordsHistoryPost200Response>, Integer, Hash)> seo_keywords_history_post_with_http_info(opts)

```ruby
begin
  # Get historical keyword data
  data, status_code, headers = api_instance.seo_keywords_history_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoKeywordsHistoryPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_keywords_history_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_keyword_history_request** | [**SeoKeywordHistoryRequest**](SeoKeywordHistoryRequest.md) |  | [optional] |

### Return type

[**SeoKeywordsHistoryPost200Response**](SeoKeywordsHistoryPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_keywords_ideas_post

> <SeoKeywordsIdeasPost200Response> seo_keywords_ideas_post(opts)

Discover keyword ideas

Expand seed keywords into related search terms that fall into the same product or service categories, each with search volume, CPC, competition, keyword difficulty, and search intent for SEO and content research.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_keyword_ideas_request: Unifapi::SeoKeywordIdeasRequest.new({keywords: ['keywords_example']}) # SeoKeywordIdeasRequest | 
}

begin
  # Discover keyword ideas
  result = api_instance.seo_keywords_ideas_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_keywords_ideas_post: #{e}"
end
```

#### Using the seo_keywords_ideas_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoKeywordsIdeasPost200Response>, Integer, Hash)> seo_keywords_ideas_post_with_http_info(opts)

```ruby
begin
  # Discover keyword ideas
  data, status_code, headers = api_instance.seo_keywords_ideas_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoKeywordsIdeasPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_keywords_ideas_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_keyword_ideas_request** | [**SeoKeywordIdeasRequest**](SeoKeywordIdeasRequest.md) |  | [optional] |

### Return type

[**SeoKeywordsIdeasPost200Response**](SeoKeywordsIdeasPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_keywords_intent_post

> <SeoKeywordsIntentPost200Response> seo_keywords_intent_post(opts)

Classify keyword search intent

Return the search intent (informational, navigational, commercial, or transactional) with probabilities for up to 1,000 keywords, for mapping keywords to the right content type.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_keyword_intent_request: Unifapi::SeoKeywordIntentRequest.new({keywords: ['keywords_example']}) # SeoKeywordIntentRequest | 
}

begin
  # Classify keyword search intent
  result = api_instance.seo_keywords_intent_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_keywords_intent_post: #{e}"
end
```

#### Using the seo_keywords_intent_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoKeywordsIntentPost200Response>, Integer, Hash)> seo_keywords_intent_post_with_http_info(opts)

```ruby
begin
  # Classify keyword search intent
  data, status_code, headers = api_instance.seo_keywords_intent_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoKeywordsIntentPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_keywords_intent_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_keyword_intent_request** | [**SeoKeywordIntentRequest**](SeoKeywordIntentRequest.md) |  | [optional] |

### Return type

[**SeoKeywordsIntentPost200Response**](SeoKeywordsIntentPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_keywords_overview_post

> <SeoKeywordsOverviewPost200Response> seo_keywords_overview_post(opts)

Look up keyword metrics

Return current SEO metrics for specified keywords, including search volume, CPC, competition, keyword difficulty, and search intent, for prioritizing keyword targets.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_keyword_overview_request: Unifapi::SeoKeywordOverviewRequest.new({keywords: ['keywords_example']}) # SeoKeywordOverviewRequest | 
}

begin
  # Look up keyword metrics
  result = api_instance.seo_keywords_overview_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_keywords_overview_post: #{e}"
end
```

#### Using the seo_keywords_overview_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoKeywordsOverviewPost200Response>, Integer, Hash)> seo_keywords_overview_post_with_http_info(opts)

```ruby
begin
  # Look up keyword metrics
  data, status_code, headers = api_instance.seo_keywords_overview_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoKeywordsOverviewPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_keywords_overview_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_keyword_overview_request** | [**SeoKeywordOverviewRequest**](SeoKeywordOverviewRequest.md) |  | [optional] |

### Return type

[**SeoKeywordsOverviewPost200Response**](SeoKeywordsOverviewPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_keywords_related_post

> <SeoKeywordsRelatedPost200Response> seo_keywords_related_post(opts)

Find related keywords

Expand a seed keyword using the 'searches related to' element, each with search volume, CPC, competition, keyword difficulty, and search intent for SEO and content research.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_related_keywords_request: Unifapi::SeoRelatedKeywordsRequest.new({keyword: 'keyword_example'}) # SeoRelatedKeywordsRequest | 
}

begin
  # Find related keywords
  result = api_instance.seo_keywords_related_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_keywords_related_post: #{e}"
end
```

#### Using the seo_keywords_related_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoKeywordsRelatedPost200Response>, Integer, Hash)> seo_keywords_related_post_with_http_info(opts)

```ruby
begin
  # Find related keywords
  data, status_code, headers = api_instance.seo_keywords_related_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoKeywordsRelatedPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_keywords_related_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_related_keywords_request** | [**SeoRelatedKeywordsRequest**](SeoRelatedKeywordsRequest.md) |  | [optional] |

### Return type

[**SeoKeywordsRelatedPost200Response**](SeoKeywordsRelatedPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_keywords_suggestions_post

> <SeoKeywordsSuggestionsPost200Response> seo_keywords_suggestions_post(opts)

Find keyword suggestions

Expand a seed keyword into long-tail search queries that include it, each with search volume, CPC, competition, keyword difficulty, and search intent for SEO and content research.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_keyword_suggestions_request: Unifapi::SeoKeywordSuggestionsRequest.new({keyword: 'keyword_example'}) # SeoKeywordSuggestionsRequest | 
}

begin
  # Find keyword suggestions
  result = api_instance.seo_keywords_suggestions_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_keywords_suggestions_post: #{e}"
end
```

#### Using the seo_keywords_suggestions_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoKeywordsSuggestionsPost200Response>, Integer, Hash)> seo_keywords_suggestions_post_with_http_info(opts)

```ruby
begin
  # Find keyword suggestions
  data, status_code, headers = api_instance.seo_keywords_suggestions_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoKeywordsSuggestionsPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_keywords_suggestions_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_keyword_suggestions_request** | [**SeoKeywordSuggestionsRequest**](SeoKeywordSuggestionsRequest.md) |  | [optional] |

### Return type

[**SeoKeywordsSuggestionsPost200Response**](SeoKeywordsSuggestionsPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## seo_serp_post

> <SeoSerpPost200Response> seo_serp_post(opts)

Collect organic SERP SEO evidence

Run one live organic SERP check for SEO optimization evidence, including target visibility, competitor domains, rich SERP features, People Also Ask context, AI Overview presence, and optional pixel ranking data.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::SeoApi.new
opts = {
  seo_serp_request: Unifapi::SeoSerpRequest.new({query: 'query_example'}) # SeoSerpRequest | 
}

begin
  # Collect organic SERP SEO evidence
  result = api_instance.seo_serp_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_serp_post: #{e}"
end
```

#### Using the seo_serp_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SeoSerpPost200Response>, Integer, Hash)> seo_serp_post_with_http_info(opts)

```ruby
begin
  # Collect organic SERP SEO evidence
  data, status_code, headers = api_instance.seo_serp_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SeoSerpPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling SeoApi->seo_serp_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **seo_serp_request** | [**SeoSerpRequest**](SeoSerpRequest.md) |  | [optional] |

### Return type

[**SeoSerpPost200Response**](SeoSerpPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

