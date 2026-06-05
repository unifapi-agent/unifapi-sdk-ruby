# Unifapi::BrowserApi

All URIs are relative to *https://api.unifapi.com*

| Method | HTTP request | Description |
| ------ | ------------ | ----------- |
| [**browser_html_post**](BrowserApi.md#browser_html_post) | **POST** /browser/html | Render a page to HTML |
| [**browser_links_post**](BrowserApi.md#browser_links_post) | **POST** /browser/links | Extract links from a page |
| [**browser_markdown_post**](BrowserApi.md#browser_markdown_post) | **POST** /browser/markdown | Render a page to Markdown |
| [**browser_screenshot_post**](BrowserApi.md#browser_screenshot_post) | **POST** /browser/screenshot | Capture a page screenshot |


## browser_html_post

> <BrowserHtmlPost200Response> browser_html_post(opts)

Render a page to HTML

Render a URL in a headless browser and return the fully rendered HTML after JavaScript execution — use it to read meta tags, structured data, and content that only appears after client-side rendering.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::BrowserApi.new
opts = {
  browser_html_request: Unifapi::BrowserHtmlRequest.new({url: 'url_example'}) # BrowserHtmlRequest | 
}

begin
  # Render a page to HTML
  result = api_instance.browser_html_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling BrowserApi->browser_html_post: #{e}"
end
```

#### Using the browser_html_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<BrowserHtmlPost200Response>, Integer, Hash)> browser_html_post_with_http_info(opts)

```ruby
begin
  # Render a page to HTML
  data, status_code, headers = api_instance.browser_html_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <BrowserHtmlPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling BrowserApi->browser_html_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **browser_html_request** | [**BrowserHtmlRequest**](BrowserHtmlRequest.md) |  | [optional] |

### Return type

[**BrowserHtmlPost200Response**](BrowserHtmlPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## browser_links_post

> <BrowserLinksPost200Response> browser_links_post(opts)

Extract links from a page

Render a URL in a headless browser and return every link on the page as absolute URLs, including links injected by JavaScript. Optionally restrict to visible links or same-domain links for internal-link and broken-link audits.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::BrowserApi.new
opts = {
  browser_links_request: Unifapi::BrowserLinksRequest.new({url: 'url_example'}) # BrowserLinksRequest | 
}

begin
  # Extract links from a page
  result = api_instance.browser_links_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling BrowserApi->browser_links_post: #{e}"
end
```

#### Using the browser_links_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<BrowserLinksPost200Response>, Integer, Hash)> browser_links_post_with_http_info(opts)

```ruby
begin
  # Extract links from a page
  data, status_code, headers = api_instance.browser_links_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <BrowserLinksPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling BrowserApi->browser_links_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **browser_links_request** | [**BrowserLinksRequest**](BrowserLinksRequest.md) |  | [optional] |

### Return type

[**BrowserLinksPost200Response**](BrowserLinksPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## browser_markdown_post

> <BrowserMarkdownPost200Response> browser_markdown_post(opts)

Render a page to Markdown

Render a URL in a headless browser (running JavaScript) and return the page as clean Markdown — ideal for content analysis, summarization, and feeding pages to language models.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::BrowserApi.new
opts = {
  browser_markdown_request: Unifapi::BrowserMarkdownRequest.new({url: 'url_example'}) # BrowserMarkdownRequest | 
}

begin
  # Render a page to Markdown
  result = api_instance.browser_markdown_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling BrowserApi->browser_markdown_post: #{e}"
end
```

#### Using the browser_markdown_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<BrowserMarkdownPost200Response>, Integer, Hash)> browser_markdown_post_with_http_info(opts)

```ruby
begin
  # Render a page to Markdown
  data, status_code, headers = api_instance.browser_markdown_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <BrowserMarkdownPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling BrowserApi->browser_markdown_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **browser_markdown_request** | [**BrowserMarkdownRequest**](BrowserMarkdownRequest.md) |  | [optional] |

### Return type

[**BrowserMarkdownPost200Response**](BrowserMarkdownPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## browser_screenshot_post

> <BrowserScreenshotPost200Response> browser_screenshot_post(opts)

Capture a page screenshot

Render a URL in a headless browser and capture a screenshot, returned as a base64-encoded image. Control the viewport, capture the full scrollable page, target a CSS selector, and choose png, jpeg, or webp output.

### Examples

```ruby
require 'time'
require 'unifapi'
# setup authorization
Unifapi.configure do |config|
  # Configure Bearer authorization: bearerAuth
  config.access_token = 'YOUR_BEARER_TOKEN'
end

api_instance = Unifapi::BrowserApi.new
opts = {
  browser_screenshot_request: Unifapi::BrowserScreenshotRequest.new({url: 'url_example'}) # BrowserScreenshotRequest | 
}

begin
  # Capture a page screenshot
  result = api_instance.browser_screenshot_post(opts)
  p result
rescue Unifapi::ApiError => e
  puts "Error when calling BrowserApi->browser_screenshot_post: #{e}"
end
```

#### Using the browser_screenshot_post_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<BrowserScreenshotPost200Response>, Integer, Hash)> browser_screenshot_post_with_http_info(opts)

```ruby
begin
  # Capture a page screenshot
  data, status_code, headers = api_instance.browser_screenshot_post_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <BrowserScreenshotPost200Response>
rescue Unifapi::ApiError => e
  puts "Error when calling BrowserApi->browser_screenshot_post_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **browser_screenshot_request** | [**BrowserScreenshotRequest**](BrowserScreenshotRequest.md) |  | [optional] |

### Return type

[**BrowserScreenshotPost200Response**](BrowserScreenshotPost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

