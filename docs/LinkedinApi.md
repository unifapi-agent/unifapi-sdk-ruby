# Unifapi::LinkedinApi

All URIs are relative to *https://api.unifapi.com*

| Method | HTTP request | Description |
| ------ | ------------ | ----------- |
| [**linkedin_ads_id_get**](LinkedinApi.md#linkedin_ads_id_get) | **GET** /linkedin/ads/{id} | Get a LinkedIn Ad Library entry by ID |
| [**linkedin_companies_slug_affiliated_get**](LinkedinApi.md#linkedin_companies_slug_affiliated_get) | **GET** /linkedin/companies/{slug}/affiliated | List a LinkedIn company&#39;s affiliated pages |
| [**linkedin_companies_slug_get**](LinkedinApi.md#linkedin_companies_slug_get) | **GET** /linkedin/companies/{slug} | Get a LinkedIn company profile by URL slug |
| [**linkedin_companies_slug_job_count_get**](LinkedinApi.md#linkedin_companies_slug_job_count_get) | **GET** /linkedin/companies/{slug}/job-count | Get the number of active jobs at a LinkedIn company |
| [**linkedin_companies_slug_jobs_get**](LinkedinApi.md#linkedin_companies_slug_jobs_get) | **GET** /linkedin/companies/{slug}/jobs | List active job postings at a LinkedIn company |
| [**linkedin_companies_slug_member_insights_get**](LinkedinApi.md#linkedin_companies_slug_member_insights_get) | **GET** /linkedin/companies/{slug}/member-insights | Get a LinkedIn company&#39;s aggregated member insights |
| [**linkedin_companies_slug_people_get**](LinkedinApi.md#linkedin_companies_slug_people_get) | **GET** /linkedin/companies/{slug}/people | List employees of a LinkedIn company |
| [**linkedin_companies_slug_posts_get**](LinkedinApi.md#linkedin_companies_slug_posts_get) | **GET** /linkedin/companies/{slug}/posts | List posts published by a LinkedIn company page |
| [**linkedin_groups_id_get**](LinkedinApi.md#linkedin_groups_id_get) | **GET** /linkedin/groups/{id} | Get a LinkedIn group by ID |
| [**linkedin_groups_id_posts_get**](LinkedinApi.md#linkedin_groups_id_posts_get) | **GET** /linkedin/groups/{id}/posts | List posts in a LinkedIn group |
| [**linkedin_jobs_id_get**](LinkedinApi.md#linkedin_jobs_id_get) | **GET** /linkedin/jobs/{id} | Get a LinkedIn job posting by ID |
| [**linkedin_posts_id_comments_comment_id_replies_get**](LinkedinApi.md#linkedin_posts_id_comments_comment_id_replies_get) | **GET** /linkedin/posts/{id}/comments/{comment_id}/replies | List replies to a LinkedIn comment |
| [**linkedin_posts_id_comments_get**](LinkedinApi.md#linkedin_posts_id_comments_get) | **GET** /linkedin/posts/{id}/comments | List top-level comments on a LinkedIn post |
| [**linkedin_posts_id_get**](LinkedinApi.md#linkedin_posts_id_get) | **GET** /linkedin/posts/{id} | Get a LinkedIn post by ID |
| [**linkedin_posts_id_reactions_get**](LinkedinApi.md#linkedin_posts_id_reactions_get) | **GET** /linkedin/posts/{id}/reactions | List users who reacted to a LinkedIn post |
| [**linkedin_posts_id_reposts_get**](LinkedinApi.md#linkedin_posts_id_reposts_get) | **GET** /linkedin/posts/{id}/reposts | List reposts of a LinkedIn post |
| [**linkedin_search_ads_get**](LinkedinApi.md#linkedin_search_ads_get) | **GET** /linkedin/search/ads | Search the LinkedIn Ad Library |
| [**linkedin_search_industries_get**](LinkedinApi.md#linkedin_search_industries_get) | **GET** /linkedin/search/industries | Resolve a free-text industry name to LinkedIn industry IDs |
| [**linkedin_search_jobs_get**](LinkedinApi.md#linkedin_search_jobs_get) | **GET** /linkedin/search/jobs | Search LinkedIn jobs by keyword and filters |
| [**linkedin_search_locations_get**](LinkedinApi.md#linkedin_search_locations_get) | **GET** /linkedin/search/locations | Resolve a free-text location into LinkedIn geocode tokens |
| [**linkedin_search_people_get**](LinkedinApi.md#linkedin_search_people_get) | **GET** /linkedin/search/people | Search LinkedIn people by name, title, company, etc. |
| [**linkedin_search_posts_get**](LinkedinApi.md#linkedin_search_posts_get) | **GET** /linkedin/search/posts | Search LinkedIn posts by keyword |
| [**linkedin_search_schools_get**](LinkedinApi.md#linkedin_search_schools_get) | **GET** /linkedin/search/schools | Search LinkedIn schools by keyword |
| [**linkedin_users_username_about_get**](LinkedinApi.md#linkedin_users_username_about_get) | **GET** /linkedin/users/{username}/about | Get a LinkedIn profile&#39;s &#39;about&#39; metadata |
| [**linkedin_users_username_certifications_get**](LinkedinApi.md#linkedin_users_username_certifications_get) | **GET** /linkedin/users/{username}/certifications | List a LinkedIn user&#39;s certifications |
| [**linkedin_users_username_comments_get**](LinkedinApi.md#linkedin_users_username_comments_get) | **GET** /linkedin/users/{username}/comments | List comments authored by a LinkedIn user |
| [**linkedin_users_username_contact_get**](LinkedinApi.md#linkedin_users_username_contact_get) | **GET** /linkedin/users/{username}/contact | Get a LinkedIn user&#39;s public contact info |
| [**linkedin_users_username_educations_get**](LinkedinApi.md#linkedin_users_username_educations_get) | **GET** /linkedin/users/{username}/educations | List a LinkedIn user&#39;s education |
| [**linkedin_users_username_experience_get**](LinkedinApi.md#linkedin_users_username_experience_get) | **GET** /linkedin/users/{username}/experience | List a LinkedIn user&#39;s work experience |
| [**linkedin_users_username_follower_count_get**](LinkedinApi.md#linkedin_users_username_follower_count_get) | **GET** /linkedin/users/{username}/follower-count | Get a LinkedIn user&#39;s follower &amp; connection counts |
| [**linkedin_users_username_get**](LinkedinApi.md#linkedin_users_username_get) | **GET** /linkedin/users/{username} | Get a LinkedIn user profile by URL slug |
| [**linkedin_users_username_honors_get**](LinkedinApi.md#linkedin_users_username_honors_get) | **GET** /linkedin/users/{username}/honors | List a LinkedIn user&#39;s honors and awards |
| [**linkedin_users_username_images_get**](LinkedinApi.md#linkedin_users_username_images_get) | **GET** /linkedin/users/{username}/images | List image posts authored by a LinkedIn user |
| [**linkedin_users_username_interests_companies_get**](LinkedinApi.md#linkedin_users_username_interests_companies_get) | **GET** /linkedin/users/{username}/interests/companies | List companies a LinkedIn user follows |
| [**linkedin_users_username_interests_groups_get**](LinkedinApi.md#linkedin_users_username_interests_groups_get) | **GET** /linkedin/users/{username}/interests/groups | List LinkedIn groups a user follows |
| [**linkedin_users_username_posts_get**](LinkedinApi.md#linkedin_users_username_posts_get) | **GET** /linkedin/users/{username}/posts | List posts authored by a LinkedIn user |
| [**linkedin_users_username_publications_get**](LinkedinApi.md#linkedin_users_username_publications_get) | **GET** /linkedin/users/{username}/publications | List a LinkedIn user&#39;s publications |
| [**linkedin_users_username_reactions_get**](LinkedinApi.md#linkedin_users_username_reactions_get) | **GET** /linkedin/users/{username}/reactions | List reactions a LinkedIn user has placed on posts |
| [**linkedin_users_username_recommendations_get**](LinkedinApi.md#linkedin_users_username_recommendations_get) | **GET** /linkedin/users/{username}/recommendations | List recommendations written for a LinkedIn user |
| [**linkedin_users_username_skills_get**](LinkedinApi.md#linkedin_users_username_skills_get) | **GET** /linkedin/users/{username}/skills | List a LinkedIn user&#39;s skills |
| [**linkedin_users_username_videos_get**](LinkedinApi.md#linkedin_users_username_videos_get) | **GET** /linkedin/users/{username}/videos | List video posts authored by a LinkedIn user |
| [**linkedin_users_username_volunteers_get**](LinkedinApi.md#linkedin_users_username_volunteers_get) | **GET** /linkedin/users/{username}/volunteers | List a LinkedIn user&#39;s volunteer experience |


## linkedin_ads_id_get

> <LinkedinAdsIdGet200Response> linkedin_ads_id_get(id)

Get a LinkedIn Ad Library entry by ID

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
id = 'id_example' # String | 

begin
  # Get a LinkedIn Ad Library entry by ID
  result = api_instance.linkedin_ads_id_get(id)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_ads_id_get: #{e}"
end
```

#### Using the linkedin_ads_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinAdsIdGet200Response>, Integer, Hash)> linkedin_ads_id_get_with_http_info(id)

```ruby
begin
  # Get a LinkedIn Ad Library entry by ID
  data, status_code, headers = api_instance.linkedin_ads_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinAdsIdGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_ads_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**LinkedinAdsIdGet200Response**](LinkedinAdsIdGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_companies_slug_affiliated_get

> <LinkedinCompaniesSlugAffiliatedGet200Response> linkedin_companies_slug_affiliated_get(slug)

List a LinkedIn company's affiliated pages

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
slug = 'slug_example' # String | 

begin
  # List a LinkedIn company's affiliated pages
  result = api_instance.linkedin_companies_slug_affiliated_get(slug)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_companies_slug_affiliated_get: #{e}"
end
```

#### Using the linkedin_companies_slug_affiliated_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinCompaniesSlugAffiliatedGet200Response>, Integer, Hash)> linkedin_companies_slug_affiliated_get_with_http_info(slug)

```ruby
begin
  # List a LinkedIn company's affiliated pages
  data, status_code, headers = api_instance.linkedin_companies_slug_affiliated_get_with_http_info(slug)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinCompaniesSlugAffiliatedGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_companies_slug_affiliated_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **slug** | **String** |  |  |

### Return type

[**LinkedinCompaniesSlugAffiliatedGet200Response**](LinkedinCompaniesSlugAffiliatedGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_companies_slug_get

> <LinkedinCompaniesSlugGet200Response> linkedin_companies_slug_get(slug)

Get a LinkedIn company profile by URL slug

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
slug = 'slug_example' # String | LinkedIn URL slug (universal_name), e.g. `microsoft`

begin
  # Get a LinkedIn company profile by URL slug
  result = api_instance.linkedin_companies_slug_get(slug)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_companies_slug_get: #{e}"
end
```

#### Using the linkedin_companies_slug_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinCompaniesSlugGet200Response>, Integer, Hash)> linkedin_companies_slug_get_with_http_info(slug)

```ruby
begin
  # Get a LinkedIn company profile by URL slug
  data, status_code, headers = api_instance.linkedin_companies_slug_get_with_http_info(slug)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinCompaniesSlugGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_companies_slug_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **slug** | **String** | LinkedIn URL slug (universal_name), e.g. &#x60;microsoft&#x60; |  |

### Return type

[**LinkedinCompaniesSlugGet200Response**](LinkedinCompaniesSlugGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_companies_slug_job_count_get

> <LinkedinCompaniesSlugJobCountGet200Response> linkedin_companies_slug_job_count_get(slug)

Get the number of active jobs at a LinkedIn company

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
slug = 'slug_example' # String | 

begin
  # Get the number of active jobs at a LinkedIn company
  result = api_instance.linkedin_companies_slug_job_count_get(slug)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_companies_slug_job_count_get: #{e}"
end
```

#### Using the linkedin_companies_slug_job_count_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinCompaniesSlugJobCountGet200Response>, Integer, Hash)> linkedin_companies_slug_job_count_get_with_http_info(slug)

```ruby
begin
  # Get the number of active jobs at a LinkedIn company
  data, status_code, headers = api_instance.linkedin_companies_slug_job_count_get_with_http_info(slug)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinCompaniesSlugJobCountGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_companies_slug_job_count_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **slug** | **String** |  |  |

### Return type

[**LinkedinCompaniesSlugJobCountGet200Response**](LinkedinCompaniesSlugJobCountGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_companies_slug_jobs_get

> <LinkedinCompaniesSlugJobsGet200Response> linkedin_companies_slug_jobs_get(slug, opts)

List active job postings at a LinkedIn company

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
slug = 'slug_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List active job postings at a LinkedIn company
  result = api_instance.linkedin_companies_slug_jobs_get(slug, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_companies_slug_jobs_get: #{e}"
end
```

#### Using the linkedin_companies_slug_jobs_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinCompaniesSlugJobsGet200Response>, Integer, Hash)> linkedin_companies_slug_jobs_get_with_http_info(slug, opts)

```ruby
begin
  # List active job postings at a LinkedIn company
  data, status_code, headers = api_instance.linkedin_companies_slug_jobs_get_with_http_info(slug, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinCompaniesSlugJobsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_companies_slug_jobs_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **slug** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**LinkedinCompaniesSlugJobsGet200Response**](LinkedinCompaniesSlugJobsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_companies_slug_member_insights_get

> <LinkedinCompaniesSlugMemberInsightsGet200Response> linkedin_companies_slug_member_insights_get(slug)

Get a LinkedIn company's aggregated member insights

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
slug = 'slug_example' # String | 

begin
  # Get a LinkedIn company's aggregated member insights
  result = api_instance.linkedin_companies_slug_member_insights_get(slug)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_companies_slug_member_insights_get: #{e}"
end
```

#### Using the linkedin_companies_slug_member_insights_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinCompaniesSlugMemberInsightsGet200Response>, Integer, Hash)> linkedin_companies_slug_member_insights_get_with_http_info(slug)

```ruby
begin
  # Get a LinkedIn company's aggregated member insights
  data, status_code, headers = api_instance.linkedin_companies_slug_member_insights_get_with_http_info(slug)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinCompaniesSlugMemberInsightsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_companies_slug_member_insights_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **slug** | **String** |  |  |

### Return type

[**LinkedinCompaniesSlugMemberInsightsGet200Response**](LinkedinCompaniesSlugMemberInsightsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_companies_slug_people_get

> <LinkedinCompaniesSlugPeopleGet200Response> linkedin_companies_slug_people_get(slug, opts)

List employees of a LinkedIn company

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
slug = 'slug_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List employees of a LinkedIn company
  result = api_instance.linkedin_companies_slug_people_get(slug, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_companies_slug_people_get: #{e}"
end
```

#### Using the linkedin_companies_slug_people_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinCompaniesSlugPeopleGet200Response>, Integer, Hash)> linkedin_companies_slug_people_get_with_http_info(slug, opts)

```ruby
begin
  # List employees of a LinkedIn company
  data, status_code, headers = api_instance.linkedin_companies_slug_people_get_with_http_info(slug, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinCompaniesSlugPeopleGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_companies_slug_people_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **slug** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**LinkedinCompaniesSlugPeopleGet200Response**](LinkedinCompaniesSlugPeopleGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_companies_slug_posts_get

> <LinkedinCompaniesSlugPostsGet200Response> linkedin_companies_slug_posts_get(slug, opts)

List posts published by a LinkedIn company page

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
slug = 'slug_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List posts published by a LinkedIn company page
  result = api_instance.linkedin_companies_slug_posts_get(slug, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_companies_slug_posts_get: #{e}"
end
```

#### Using the linkedin_companies_slug_posts_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinCompaniesSlugPostsGet200Response>, Integer, Hash)> linkedin_companies_slug_posts_get_with_http_info(slug, opts)

```ruby
begin
  # List posts published by a LinkedIn company page
  data, status_code, headers = api_instance.linkedin_companies_slug_posts_get_with_http_info(slug, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinCompaniesSlugPostsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_companies_slug_posts_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **slug** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**LinkedinCompaniesSlugPostsGet200Response**](LinkedinCompaniesSlugPostsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_groups_id_get

> <LinkedinGroupsIdGet200Response> linkedin_groups_id_get(id)

Get a LinkedIn group by ID

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
id = 'id_example' # String | 

begin
  # Get a LinkedIn group by ID
  result = api_instance.linkedin_groups_id_get(id)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_groups_id_get: #{e}"
end
```

#### Using the linkedin_groups_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinGroupsIdGet200Response>, Integer, Hash)> linkedin_groups_id_get_with_http_info(id)

```ruby
begin
  # Get a LinkedIn group by ID
  data, status_code, headers = api_instance.linkedin_groups_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinGroupsIdGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_groups_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**LinkedinGroupsIdGet200Response**](LinkedinGroupsIdGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_groups_id_posts_get

> <LinkedinCompaniesSlugPostsGet200Response> linkedin_groups_id_posts_get(id, opts)

List posts in a LinkedIn group

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
id = 'id_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List posts in a LinkedIn group
  result = api_instance.linkedin_groups_id_posts_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_groups_id_posts_get: #{e}"
end
```

#### Using the linkedin_groups_id_posts_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinCompaniesSlugPostsGet200Response>, Integer, Hash)> linkedin_groups_id_posts_get_with_http_info(id, opts)

```ruby
begin
  # List posts in a LinkedIn group
  data, status_code, headers = api_instance.linkedin_groups_id_posts_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinCompaniesSlugPostsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_groups_id_posts_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**LinkedinCompaniesSlugPostsGet200Response**](LinkedinCompaniesSlugPostsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_jobs_id_get

> <LinkedinJobsIdGet200Response> linkedin_jobs_id_get(id, opts)

Get a LinkedIn job posting by ID

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
id = 'id_example' # String | 
opts = {
  include_skills: 'true' # String | 
}

begin
  # Get a LinkedIn job posting by ID
  result = api_instance.linkedin_jobs_id_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_jobs_id_get: #{e}"
end
```

#### Using the linkedin_jobs_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinJobsIdGet200Response>, Integer, Hash)> linkedin_jobs_id_get_with_http_info(id, opts)

```ruby
begin
  # Get a LinkedIn job posting by ID
  data, status_code, headers = api_instance.linkedin_jobs_id_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinJobsIdGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_jobs_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **include_skills** | **String** |  | [optional] |

### Return type

[**LinkedinJobsIdGet200Response**](LinkedinJobsIdGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_posts_id_comments_comment_id_replies_get

> <LinkedinPostsIdCommentsCommentIdRepliesGet200Response> linkedin_posts_id_comments_comment_id_replies_get(id, comment_id, opts)

List replies to a LinkedIn comment

`cursor` here is LinkedIn's `previous_replies_token`. On the first page, send no cursor — LinkedIn's source still expects the param, so the gateway passes `-` as the sentinel it documents.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
id = 'id_example' # String | 
comment_id = 'comment_id_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List replies to a LinkedIn comment
  result = api_instance.linkedin_posts_id_comments_comment_id_replies_get(id, comment_id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_posts_id_comments_comment_id_replies_get: #{e}"
end
```

#### Using the linkedin_posts_id_comments_comment_id_replies_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinPostsIdCommentsCommentIdRepliesGet200Response>, Integer, Hash)> linkedin_posts_id_comments_comment_id_replies_get_with_http_info(id, comment_id, opts)

```ruby
begin
  # List replies to a LinkedIn comment
  data, status_code, headers = api_instance.linkedin_posts_id_comments_comment_id_replies_get_with_http_info(id, comment_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinPostsIdCommentsCommentIdRepliesGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_posts_id_comments_comment_id_replies_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **comment_id** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**LinkedinPostsIdCommentsCommentIdRepliesGet200Response**](LinkedinPostsIdCommentsCommentIdRepliesGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_posts_id_comments_get

> <LinkedinPostsIdCommentsCommentIdRepliesGet200Response> linkedin_posts_id_comments_get(id, opts)

List top-level comments on a LinkedIn post

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
id = 'id_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List top-level comments on a LinkedIn post
  result = api_instance.linkedin_posts_id_comments_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_posts_id_comments_get: #{e}"
end
```

#### Using the linkedin_posts_id_comments_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinPostsIdCommentsCommentIdRepliesGet200Response>, Integer, Hash)> linkedin_posts_id_comments_get_with_http_info(id, opts)

```ruby
begin
  # List top-level comments on a LinkedIn post
  data, status_code, headers = api_instance.linkedin_posts_id_comments_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinPostsIdCommentsCommentIdRepliesGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_posts_id_comments_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**LinkedinPostsIdCommentsCommentIdRepliesGet200Response**](LinkedinPostsIdCommentsCommentIdRepliesGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_posts_id_get

> <LinkedinPostsIdGet200Response> linkedin_posts_id_get(id)

Get a LinkedIn post by ID

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
id = 'id_example' # String | 

begin
  # Get a LinkedIn post by ID
  result = api_instance.linkedin_posts_id_get(id)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_posts_id_get: #{e}"
end
```

#### Using the linkedin_posts_id_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinPostsIdGet200Response>, Integer, Hash)> linkedin_posts_id_get_with_http_info(id)

```ruby
begin
  # Get a LinkedIn post by ID
  data, status_code, headers = api_instance.linkedin_posts_id_get_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinPostsIdGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_posts_id_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |

### Return type

[**LinkedinPostsIdGet200Response**](LinkedinPostsIdGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_posts_id_reactions_get

> <LinkedinCompaniesSlugPeopleGet200Response> linkedin_posts_id_reactions_get(id, opts)

List users who reacted to a LinkedIn post

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
id = 'id_example' # String | 
opts = {
  cursor: 'cursor_example', # String | 
  type: 'all' # String | Filter by reaction type. `all` returns every reaction (default).
}

begin
  # List users who reacted to a LinkedIn post
  result = api_instance.linkedin_posts_id_reactions_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_posts_id_reactions_get: #{e}"
end
```

#### Using the linkedin_posts_id_reactions_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinCompaniesSlugPeopleGet200Response>, Integer, Hash)> linkedin_posts_id_reactions_get_with_http_info(id, opts)

```ruby
begin
  # List users who reacted to a LinkedIn post
  data, status_code, headers = api_instance.linkedin_posts_id_reactions_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinCompaniesSlugPeopleGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_posts_id_reactions_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **cursor** | **String** |  | [optional] |
| **type** | **String** | Filter by reaction type. &#x60;all&#x60; returns every reaction (default). | [optional][default to &#39;all&#39;] |

### Return type

[**LinkedinCompaniesSlugPeopleGet200Response**](LinkedinCompaniesSlugPeopleGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_posts_id_reposts_get

> <LinkedinCompaniesSlugPostsGet200Response> linkedin_posts_id_reposts_get(id, opts)

List reposts of a LinkedIn post

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
id = 'id_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List reposts of a LinkedIn post
  result = api_instance.linkedin_posts_id_reposts_get(id, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_posts_id_reposts_get: #{e}"
end
```

#### Using the linkedin_posts_id_reposts_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinCompaniesSlugPostsGet200Response>, Integer, Hash)> linkedin_posts_id_reposts_get_with_http_info(id, opts)

```ruby
begin
  # List reposts of a LinkedIn post
  data, status_code, headers = api_instance.linkedin_posts_id_reposts_get_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinCompaniesSlugPostsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_posts_id_reposts_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**LinkedinCompaniesSlugPostsGet200Response**](LinkedinCompaniesSlugPostsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_search_ads_get

> <LinkedinSearchAdsGet200Response> linkedin_search_ads_get(opts)

Search the LinkedIn Ad Library

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
opts = {
  cursor: 'cursor_example', # String | 
  keyword: 'keyword_example', # String | 
  advertiser_name: 'advertiser_name_example', # String | 
  country: 'country_example', # String | ISO-3166-1 alpha-2 code, e.g. `US`
  date: 'date_example' # String | 
}

begin
  # Search the LinkedIn Ad Library
  result = api_instance.linkedin_search_ads_get(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_search_ads_get: #{e}"
end
```

#### Using the linkedin_search_ads_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinSearchAdsGet200Response>, Integer, Hash)> linkedin_search_ads_get_with_http_info(opts)

```ruby
begin
  # Search the LinkedIn Ad Library
  data, status_code, headers = api_instance.linkedin_search_ads_get_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinSearchAdsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_search_ads_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **cursor** | **String** |  | [optional] |
| **keyword** | **String** |  | [optional] |
| **advertiser_name** | **String** |  | [optional] |
| **country** | **String** | ISO-3166-1 alpha-2 code, e.g. &#x60;US&#x60; | [optional] |
| **date** | **String** |  | [optional] |

### Return type

[**LinkedinSearchAdsGet200Response**](LinkedinSearchAdsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_search_industries_get

> <LinkedinSearchIndustriesGet200Response> linkedin_search_industries_get(keyword)

Resolve a free-text industry name to LinkedIn industry IDs

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
keyword = 'keyword_example' # String | 

begin
  # Resolve a free-text industry name to LinkedIn industry IDs
  result = api_instance.linkedin_search_industries_get(keyword)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_search_industries_get: #{e}"
end
```

#### Using the linkedin_search_industries_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinSearchIndustriesGet200Response>, Integer, Hash)> linkedin_search_industries_get_with_http_info(keyword)

```ruby
begin
  # Resolve a free-text industry name to LinkedIn industry IDs
  data, status_code, headers = api_instance.linkedin_search_industries_get_with_http_info(keyword)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinSearchIndustriesGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_search_industries_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **keyword** | **String** |  |  |

### Return type

[**LinkedinSearchIndustriesGet200Response**](LinkedinSearchIndustriesGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_search_jobs_get

> <LinkedinCompaniesSlugJobsGet200Response> linkedin_search_jobs_get(keyword, opts)

Search LinkedIn jobs by keyword and filters

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
keyword = 'keyword_example' # String | Free-text search query
opts = {
  cursor: 'cursor_example', # String | 
  sort_by: 'sort_by_example', # String | 
  date_posted: 'date_posted_example', # String | 
  geocode: 'geocode_example', # String | 
  company: 'company_example', # String | 
  experience_level: 'experience_level_example', # String | 
  remote: 'remote_example', # String | 
  job_type: 'job_type_example', # String | 
  easy_apply: 'true', # String | 
  has_verifications: 'true', # String | 
  under_10_applicants: 'true', # String | 
  fair_chance_employer: 'true' # String | 
}

begin
  # Search LinkedIn jobs by keyword and filters
  result = api_instance.linkedin_search_jobs_get(keyword, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_search_jobs_get: #{e}"
end
```

#### Using the linkedin_search_jobs_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinCompaniesSlugJobsGet200Response>, Integer, Hash)> linkedin_search_jobs_get_with_http_info(keyword, opts)

```ruby
begin
  # Search LinkedIn jobs by keyword and filters
  data, status_code, headers = api_instance.linkedin_search_jobs_get_with_http_info(keyword, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinCompaniesSlugJobsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_search_jobs_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **keyword** | **String** | Free-text search query |  |
| **cursor** | **String** |  | [optional] |
| **sort_by** | **String** |  | [optional] |
| **date_posted** | **String** |  | [optional] |
| **geocode** | **String** |  | [optional] |
| **company** | **String** |  | [optional] |
| **experience_level** | **String** |  | [optional] |
| **remote** | **String** |  | [optional] |
| **job_type** | **String** |  | [optional] |
| **easy_apply** | **String** |  | [optional] |
| **has_verifications** | **String** |  | [optional] |
| **under_10_applicants** | **String** |  | [optional] |
| **fair_chance_employer** | **String** |  | [optional] |

### Return type

[**LinkedinCompaniesSlugJobsGet200Response**](LinkedinCompaniesSlugJobsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_search_locations_get

> <LinkedinSearchLocationsGet200Response> linkedin_search_locations_get(keyword)

Resolve a free-text location into LinkedIn geocode tokens

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
keyword = 'keyword_example' # String | 

begin
  # Resolve a free-text location into LinkedIn geocode tokens
  result = api_instance.linkedin_search_locations_get(keyword)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_search_locations_get: #{e}"
end
```

#### Using the linkedin_search_locations_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinSearchLocationsGet200Response>, Integer, Hash)> linkedin_search_locations_get_with_http_info(keyword)

```ruby
begin
  # Resolve a free-text location into LinkedIn geocode tokens
  data, status_code, headers = api_instance.linkedin_search_locations_get_with_http_info(keyword)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinSearchLocationsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_search_locations_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **keyword** | **String** |  |  |

### Return type

[**LinkedinSearchLocationsGet200Response**](LinkedinSearchLocationsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_search_people_get

> <LinkedinCompaniesSlugPeopleGet200Response> linkedin_search_people_get(opts)

Search LinkedIn people by name, title, company, etc.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
opts = {
  cursor: 'cursor_example', # String | 
  name: 'name_example', # String | 
  first_name: 'first_name_example', # String | 
  last_name: 'last_name_example', # String | 
  title: 'title_example', # String | 
  company: 'company_example', # String | 
  school: 'school_example', # String | 
  geocode_location: 'geocode_location_example', # String | 
  current_company: 'current_company_example', # String | 
  profile_language: 'profile_language_example', # String | 
  industry: 'industry_example', # String | 
  service_category: 'service_category_example' # String | 
}

begin
  # Search LinkedIn people by name, title, company, etc.
  result = api_instance.linkedin_search_people_get(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_search_people_get: #{e}"
end
```

#### Using the linkedin_search_people_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinCompaniesSlugPeopleGet200Response>, Integer, Hash)> linkedin_search_people_get_with_http_info(opts)

```ruby
begin
  # Search LinkedIn people by name, title, company, etc.
  data, status_code, headers = api_instance.linkedin_search_people_get_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinCompaniesSlugPeopleGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_search_people_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **cursor** | **String** |  | [optional] |
| **name** | **String** |  | [optional] |
| **first_name** | **String** |  | [optional] |
| **last_name** | **String** |  | [optional] |
| **title** | **String** |  | [optional] |
| **company** | **String** |  | [optional] |
| **school** | **String** |  | [optional] |
| **geocode_location** | **String** |  | [optional] |
| **current_company** | **String** |  | [optional] |
| **profile_language** | **String** |  | [optional] |
| **industry** | **String** |  | [optional] |
| **service_category** | **String** |  | [optional] |

### Return type

[**LinkedinCompaniesSlugPeopleGet200Response**](LinkedinCompaniesSlugPeopleGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_search_posts_get

> <LinkedinSearchPostsGet200Response> linkedin_search_posts_get(keyword, opts)

Search LinkedIn posts by keyword

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
keyword = 'keyword_example' # String | 
opts = {
  cursor: 'cursor_example', # String | 
  date_posted: 'date_posted_example', # String | 
  sort_by: 'sort_by_example', # String | 
  from_member: 'from_member_example', # String | 
  from_company: 'from_company_example', # String | 
  content_type: 'content_type_example' # String | 
}

begin
  # Search LinkedIn posts by keyword
  result = api_instance.linkedin_search_posts_get(keyword, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_search_posts_get: #{e}"
end
```

#### Using the linkedin_search_posts_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinSearchPostsGet200Response>, Integer, Hash)> linkedin_search_posts_get_with_http_info(keyword, opts)

```ruby
begin
  # Search LinkedIn posts by keyword
  data, status_code, headers = api_instance.linkedin_search_posts_get_with_http_info(keyword, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinSearchPostsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_search_posts_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **keyword** | **String** |  |  |
| **cursor** | **String** |  | [optional] |
| **date_posted** | **String** |  | [optional] |
| **sort_by** | **String** |  | [optional] |
| **from_member** | **String** |  | [optional] |
| **from_company** | **String** |  | [optional] |
| **content_type** | **String** |  | [optional] |

### Return type

[**LinkedinSearchPostsGet200Response**](LinkedinSearchPostsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_search_schools_get

> <LinkedinSearchSchoolsGet200Response> linkedin_search_schools_get(keyword, opts)

Search LinkedIn schools by keyword

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
keyword = 'keyword_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # Search LinkedIn schools by keyword
  result = api_instance.linkedin_search_schools_get(keyword, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_search_schools_get: #{e}"
end
```

#### Using the linkedin_search_schools_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinSearchSchoolsGet200Response>, Integer, Hash)> linkedin_search_schools_get_with_http_info(keyword, opts)

```ruby
begin
  # Search LinkedIn schools by keyword
  data, status_code, headers = api_instance.linkedin_search_schools_get_with_http_info(keyword, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinSearchSchoolsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_search_schools_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **keyword** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**LinkedinSearchSchoolsGet200Response**](LinkedinSearchSchoolsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_users_username_about_get

> <LinkedinUsersUsernameAboutGet200Response> linkedin_users_username_about_get(username)

Get a LinkedIn profile's 'about' metadata

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
username = 'username_example' # String | 

begin
  # Get a LinkedIn profile's 'about' metadata
  result = api_instance.linkedin_users_username_about_get(username)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_about_get: #{e}"
end
```

#### Using the linkedin_users_username_about_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinUsersUsernameAboutGet200Response>, Integer, Hash)> linkedin_users_username_about_get_with_http_info(username)

```ruby
begin
  # Get a LinkedIn profile's 'about' metadata
  data, status_code, headers = api_instance.linkedin_users_username_about_get_with_http_info(username)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinUsersUsernameAboutGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_about_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |

### Return type

[**LinkedinUsersUsernameAboutGet200Response**](LinkedinUsersUsernameAboutGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_users_username_certifications_get

> <LinkedinUsersUsernameCertificationsGet200Response> linkedin_users_username_certifications_get(username, opts)

List a LinkedIn user's certifications

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
username = 'username_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List a LinkedIn user's certifications
  result = api_instance.linkedin_users_username_certifications_get(username, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_certifications_get: #{e}"
end
```

#### Using the linkedin_users_username_certifications_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinUsersUsernameCertificationsGet200Response>, Integer, Hash)> linkedin_users_username_certifications_get_with_http_info(username, opts)

```ruby
begin
  # List a LinkedIn user's certifications
  data, status_code, headers = api_instance.linkedin_users_username_certifications_get_with_http_info(username, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinUsersUsernameCertificationsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_certifications_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**LinkedinUsersUsernameCertificationsGet200Response**](LinkedinUsersUsernameCertificationsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_users_username_comments_get

> <LinkedinUsersUsernameCommentsGet200Response> linkedin_users_username_comments_get(username, opts)

List comments authored by a LinkedIn user

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
username = 'username_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List comments authored by a LinkedIn user
  result = api_instance.linkedin_users_username_comments_get(username, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_comments_get: #{e}"
end
```

#### Using the linkedin_users_username_comments_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinUsersUsernameCommentsGet200Response>, Integer, Hash)> linkedin_users_username_comments_get_with_http_info(username, opts)

```ruby
begin
  # List comments authored by a LinkedIn user
  data, status_code, headers = api_instance.linkedin_users_username_comments_get_with_http_info(username, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinUsersUsernameCommentsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_comments_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**LinkedinUsersUsernameCommentsGet200Response**](LinkedinUsersUsernameCommentsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_users_username_contact_get

> <LinkedinUsersUsernameContactGet200Response> linkedin_users_username_contact_get(username)

Get a LinkedIn user's public contact info

Returns the contact block (websites, phone numbers, twitter handles, address, wechat) the user has chosen to publish on LinkedIn.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
username = 'username_example' # String | 

begin
  # Get a LinkedIn user's public contact info
  result = api_instance.linkedin_users_username_contact_get(username)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_contact_get: #{e}"
end
```

#### Using the linkedin_users_username_contact_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinUsersUsernameContactGet200Response>, Integer, Hash)> linkedin_users_username_contact_get_with_http_info(username)

```ruby
begin
  # Get a LinkedIn user's public contact info
  data, status_code, headers = api_instance.linkedin_users_username_contact_get_with_http_info(username)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinUsersUsernameContactGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_contact_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |

### Return type

[**LinkedinUsersUsernameContactGet200Response**](LinkedinUsersUsernameContactGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_users_username_educations_get

> <LinkedinUsersUsernameEducationsGet200Response> linkedin_users_username_educations_get(username, opts)

List a LinkedIn user's education

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
username = 'username_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List a LinkedIn user's education
  result = api_instance.linkedin_users_username_educations_get(username, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_educations_get: #{e}"
end
```

#### Using the linkedin_users_username_educations_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinUsersUsernameEducationsGet200Response>, Integer, Hash)> linkedin_users_username_educations_get_with_http_info(username, opts)

```ruby
begin
  # List a LinkedIn user's education
  data, status_code, headers = api_instance.linkedin_users_username_educations_get_with_http_info(username, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinUsersUsernameEducationsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_educations_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**LinkedinUsersUsernameEducationsGet200Response**](LinkedinUsersUsernameEducationsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_users_username_experience_get

> <LinkedinUsersUsernameExperienceGet200Response> linkedin_users_username_experience_get(username, opts)

List a LinkedIn user's work experience

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
username = 'username_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List a LinkedIn user's work experience
  result = api_instance.linkedin_users_username_experience_get(username, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_experience_get: #{e}"
end
```

#### Using the linkedin_users_username_experience_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinUsersUsernameExperienceGet200Response>, Integer, Hash)> linkedin_users_username_experience_get_with_http_info(username, opts)

```ruby
begin
  # List a LinkedIn user's work experience
  data, status_code, headers = api_instance.linkedin_users_username_experience_get_with_http_info(username, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinUsersUsernameExperienceGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_experience_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**LinkedinUsersUsernameExperienceGet200Response**](LinkedinUsersUsernameExperienceGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_users_username_follower_count_get

> <LinkedinUsersUsernameFollowerCountGet200Response> linkedin_users_username_follower_count_get(username)

Get a LinkedIn user's follower & connection counts

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
username = 'username_example' # String | 

begin
  # Get a LinkedIn user's follower & connection counts
  result = api_instance.linkedin_users_username_follower_count_get(username)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_follower_count_get: #{e}"
end
```

#### Using the linkedin_users_username_follower_count_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinUsersUsernameFollowerCountGet200Response>, Integer, Hash)> linkedin_users_username_follower_count_get_with_http_info(username)

```ruby
begin
  # Get a LinkedIn user's follower & connection counts
  data, status_code, headers = api_instance.linkedin_users_username_follower_count_get_with_http_info(username)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinUsersUsernameFollowerCountGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_follower_count_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |

### Return type

[**LinkedinUsersUsernameFollowerCountGet200Response**](LinkedinUsersUsernameFollowerCountGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_users_username_get

> <LinkedinUsersUsernameGet200Response> linkedin_users_username_get(username)

Get a LinkedIn user profile by URL slug

Returns the canonical LinkedIn profile for the given URL slug (`public_identifier`). Returns 404 not_found if no such user exists.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
username = 'username_example' # String | LinkedIn URL slug, e.g. `williamhgates`

begin
  # Get a LinkedIn user profile by URL slug
  result = api_instance.linkedin_users_username_get(username)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_get: #{e}"
end
```

#### Using the linkedin_users_username_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinUsersUsernameGet200Response>, Integer, Hash)> linkedin_users_username_get_with_http_info(username)

```ruby
begin
  # Get a LinkedIn user profile by URL slug
  data, status_code, headers = api_instance.linkedin_users_username_get_with_http_info(username)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinUsersUsernameGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** | LinkedIn URL slug, e.g. &#x60;williamhgates&#x60; |  |

### Return type

[**LinkedinUsersUsernameGet200Response**](LinkedinUsersUsernameGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_users_username_honors_get

> <LinkedinUsersUsernameHonorsGet200Response> linkedin_users_username_honors_get(username, opts)

List a LinkedIn user's honors and awards

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
username = 'username_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List a LinkedIn user's honors and awards
  result = api_instance.linkedin_users_username_honors_get(username, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_honors_get: #{e}"
end
```

#### Using the linkedin_users_username_honors_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinUsersUsernameHonorsGet200Response>, Integer, Hash)> linkedin_users_username_honors_get_with_http_info(username, opts)

```ruby
begin
  # List a LinkedIn user's honors and awards
  data, status_code, headers = api_instance.linkedin_users_username_honors_get_with_http_info(username, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinUsersUsernameHonorsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_honors_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**LinkedinUsersUsernameHonorsGet200Response**](LinkedinUsersUsernameHonorsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_users_username_images_get

> <LinkedinUsersUsernameImagesGet200Response> linkedin_users_username_images_get(username, opts)

List image posts authored by a LinkedIn user

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
username = 'username_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List image posts authored by a LinkedIn user
  result = api_instance.linkedin_users_username_images_get(username, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_images_get: #{e}"
end
```

#### Using the linkedin_users_username_images_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinUsersUsernameImagesGet200Response>, Integer, Hash)> linkedin_users_username_images_get_with_http_info(username, opts)

```ruby
begin
  # List image posts authored by a LinkedIn user
  data, status_code, headers = api_instance.linkedin_users_username_images_get_with_http_info(username, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinUsersUsernameImagesGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_images_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**LinkedinUsersUsernameImagesGet200Response**](LinkedinUsersUsernameImagesGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_users_username_interests_companies_get

> <LinkedinUsersUsernameInterestsCompaniesGet200Response> linkedin_users_username_interests_companies_get(username, opts)

List companies a LinkedIn user follows

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
username = 'username_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List companies a LinkedIn user follows
  result = api_instance.linkedin_users_username_interests_companies_get(username, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_interests_companies_get: #{e}"
end
```

#### Using the linkedin_users_username_interests_companies_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinUsersUsernameInterestsCompaniesGet200Response>, Integer, Hash)> linkedin_users_username_interests_companies_get_with_http_info(username, opts)

```ruby
begin
  # List companies a LinkedIn user follows
  data, status_code, headers = api_instance.linkedin_users_username_interests_companies_get_with_http_info(username, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinUsersUsernameInterestsCompaniesGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_interests_companies_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**LinkedinUsersUsernameInterestsCompaniesGet200Response**](LinkedinUsersUsernameInterestsCompaniesGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_users_username_interests_groups_get

> <LinkedinUsersUsernameInterestsGroupsGet200Response> linkedin_users_username_interests_groups_get(username, opts)

List LinkedIn groups a user follows

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
username = 'username_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List LinkedIn groups a user follows
  result = api_instance.linkedin_users_username_interests_groups_get(username, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_interests_groups_get: #{e}"
end
```

#### Using the linkedin_users_username_interests_groups_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinUsersUsernameInterestsGroupsGet200Response>, Integer, Hash)> linkedin_users_username_interests_groups_get_with_http_info(username, opts)

```ruby
begin
  # List LinkedIn groups a user follows
  data, status_code, headers = api_instance.linkedin_users_username_interests_groups_get_with_http_info(username, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinUsersUsernameInterestsGroupsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_interests_groups_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**LinkedinUsersUsernameInterestsGroupsGet200Response**](LinkedinUsersUsernameInterestsGroupsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_users_username_posts_get

> <LinkedinCompaniesSlugPostsGet200Response> linkedin_users_username_posts_get(username, opts)

List posts authored by a LinkedIn user

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
username = 'username_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List posts authored by a LinkedIn user
  result = api_instance.linkedin_users_username_posts_get(username, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_posts_get: #{e}"
end
```

#### Using the linkedin_users_username_posts_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinCompaniesSlugPostsGet200Response>, Integer, Hash)> linkedin_users_username_posts_get_with_http_info(username, opts)

```ruby
begin
  # List posts authored by a LinkedIn user
  data, status_code, headers = api_instance.linkedin_users_username_posts_get_with_http_info(username, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinCompaniesSlugPostsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_posts_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**LinkedinCompaniesSlugPostsGet200Response**](LinkedinCompaniesSlugPostsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_users_username_publications_get

> <LinkedinUsersUsernamePublicationsGet200Response> linkedin_users_username_publications_get(username, opts)

List a LinkedIn user's publications

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
username = 'username_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List a LinkedIn user's publications
  result = api_instance.linkedin_users_username_publications_get(username, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_publications_get: #{e}"
end
```

#### Using the linkedin_users_username_publications_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinUsersUsernamePublicationsGet200Response>, Integer, Hash)> linkedin_users_username_publications_get_with_http_info(username, opts)

```ruby
begin
  # List a LinkedIn user's publications
  data, status_code, headers = api_instance.linkedin_users_username_publications_get_with_http_info(username, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinUsersUsernamePublicationsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_publications_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**LinkedinUsersUsernamePublicationsGet200Response**](LinkedinUsersUsernamePublicationsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_users_username_reactions_get

> <LinkedinUsersUsernameReactionsGet200Response> linkedin_users_username_reactions_get(username, opts)

List reactions a LinkedIn user has placed on posts

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
username = 'username_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List reactions a LinkedIn user has placed on posts
  result = api_instance.linkedin_users_username_reactions_get(username, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_reactions_get: #{e}"
end
```

#### Using the linkedin_users_username_reactions_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinUsersUsernameReactionsGet200Response>, Integer, Hash)> linkedin_users_username_reactions_get_with_http_info(username, opts)

```ruby
begin
  # List reactions a LinkedIn user has placed on posts
  data, status_code, headers = api_instance.linkedin_users_username_reactions_get_with_http_info(username, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinUsersUsernameReactionsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_reactions_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**LinkedinUsersUsernameReactionsGet200Response**](LinkedinUsersUsernameReactionsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_users_username_recommendations_get

> <LinkedinUsersUsernameRecommendationsGet200Response> linkedin_users_username_recommendations_get(username, opts)

List recommendations written for a LinkedIn user

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
username = 'username_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List recommendations written for a LinkedIn user
  result = api_instance.linkedin_users_username_recommendations_get(username, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_recommendations_get: #{e}"
end
```

#### Using the linkedin_users_username_recommendations_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinUsersUsernameRecommendationsGet200Response>, Integer, Hash)> linkedin_users_username_recommendations_get_with_http_info(username, opts)

```ruby
begin
  # List recommendations written for a LinkedIn user
  data, status_code, headers = api_instance.linkedin_users_username_recommendations_get_with_http_info(username, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinUsersUsernameRecommendationsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_recommendations_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**LinkedinUsersUsernameRecommendationsGet200Response**](LinkedinUsersUsernameRecommendationsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_users_username_skills_get

> <LinkedinUsersUsernameSkillsGet200Response> linkedin_users_username_skills_get(username, opts)

List a LinkedIn user's skills

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
username = 'username_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List a LinkedIn user's skills
  result = api_instance.linkedin_users_username_skills_get(username, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_skills_get: #{e}"
end
```

#### Using the linkedin_users_username_skills_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinUsersUsernameSkillsGet200Response>, Integer, Hash)> linkedin_users_username_skills_get_with_http_info(username, opts)

```ruby
begin
  # List a LinkedIn user's skills
  data, status_code, headers = api_instance.linkedin_users_username_skills_get_with_http_info(username, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinUsersUsernameSkillsGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_skills_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**LinkedinUsersUsernameSkillsGet200Response**](LinkedinUsersUsernameSkillsGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_users_username_videos_get

> <LinkedinUsersUsernameVideosGet200Response> linkedin_users_username_videos_get(username, opts)

List video posts authored by a LinkedIn user

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
username = 'username_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List video posts authored by a LinkedIn user
  result = api_instance.linkedin_users_username_videos_get(username, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_videos_get: #{e}"
end
```

#### Using the linkedin_users_username_videos_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinUsersUsernameVideosGet200Response>, Integer, Hash)> linkedin_users_username_videos_get_with_http_info(username, opts)

```ruby
begin
  # List video posts authored by a LinkedIn user
  data, status_code, headers = api_instance.linkedin_users_username_videos_get_with_http_info(username, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinUsersUsernameVideosGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_videos_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**LinkedinUsersUsernameVideosGet200Response**](LinkedinUsersUsernameVideosGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## linkedin_users_username_volunteers_get

> <LinkedinUsersUsernameVolunteersGet200Response> linkedin_users_username_volunteers_get(username, opts)

List a LinkedIn user's volunteer experience

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::LinkedinApi.new
username = 'username_example' # String | 
opts = {
  cursor: 'cursor_example' # String | 
}

begin
  # List a LinkedIn user's volunteer experience
  result = api_instance.linkedin_users_username_volunteers_get(username, opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_volunteers_get: #{e}"
end
```

#### Using the linkedin_users_username_volunteers_get_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LinkedinUsersUsernameVolunteersGet200Response>, Integer, Hash)> linkedin_users_username_volunteers_get_with_http_info(username, opts)

```ruby
begin
  # List a LinkedIn user's volunteer experience
  data, status_code, headers = api_instance.linkedin_users_username_volunteers_get_with_http_info(username, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LinkedinUsersUsernameVolunteersGet200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling LinkedinApi->linkedin_users_username_volunteers_get_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |
| **cursor** | **String** |  | [optional] |

### Return type

[**LinkedinUsersUsernameVolunteersGet200Response**](LinkedinUsersUsernameVolunteersGet200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

