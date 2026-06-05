# Unifapi::BrowserScreenshotRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **url** | **String** | Absolute http(s) URL of the page to render. |  |
| **wait_until** | **String** | When navigation is considered complete. &#x60;networkidle0&#x60; waits for the network to go idle (best for JavaScript-heavy pages); &#x60;load&#x60; is fastest. | [optional] |
| **timeout_ms** | **Integer** | Navigation timeout in milliseconds (1000–60000). | [optional] |
| **viewport** | [**BrowserScreenshotRequestViewport**](BrowserScreenshotRequestViewport.md) |  | [optional] |
| **full_page** | **Boolean** | Capture the full scrollable page instead of just the viewport. | [optional] |
| **format** | **String** | Output image format. | [optional][default to &#39;png&#39;] |
| **quality** | **Integer** | Compression quality (0–100). Only valid for &#x60;jpeg&#x60; and &#x60;webp&#x60;. | [optional] |
| **selector** | **String** | Capture only the first element matching this CSS selector. | [optional] |
| **omit_background** | **Boolean** | Render a transparent background (ignored for &#x60;jpeg&#x60;). | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::BrowserScreenshotRequest.new(
  url: null,
  wait_until: null,
  timeout_ms: null,
  viewport: null,
  full_page: null,
  format: null,
  quality: null,
  selector: null,
  omit_background: null
)
```

