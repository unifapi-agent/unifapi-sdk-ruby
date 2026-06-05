# Unifapi::BrowserMarkdownRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **url** | **String** | Absolute http(s) URL of the page to render. |  |
| **wait_until** | **String** | When navigation is considered complete. &#x60;networkidle0&#x60; waits for the network to go idle (best for JavaScript-heavy pages); &#x60;load&#x60; is fastest. | [optional] |
| **timeout_ms** | **Integer** | Navigation timeout in milliseconds (1000–60000). | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::BrowserMarkdownRequest.new(
  url: null,
  wait_until: null,
  timeout_ms: null
)
```

