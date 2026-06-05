# Unifapi::BrowserLinksRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **url** | **String** | Absolute http(s) URL of the page to render. |  |
| **wait_until** | **String** | When navigation is considered complete. &#x60;networkidle0&#x60; waits for the network to go idle (best for JavaScript-heavy pages); &#x60;load&#x60; is fastest. | [optional] |
| **timeout_ms** | **Integer** | Navigation timeout in milliseconds (1000–60000). | [optional] |
| **visible_links_only** | **Boolean** | Only return links visible in the rendered viewport. | [optional] |
| **exclude_external_links** | **Boolean** | Drop links that point to a different domain than the page. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::BrowserLinksRequest.new(
  url: null,
  wait_until: null,
  timeout_ms: null,
  visible_links_only: null,
  exclude_external_links: null
)
```

