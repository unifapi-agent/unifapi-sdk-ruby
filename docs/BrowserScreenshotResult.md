# Unifapi::BrowserScreenshotResult

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **url** | **String** | The rendered URL. |  |
| **format** | **String** | Output image format. |  |
| **image_base64** | **String** | Base64-encoded image bytes. |  |
| **size_bytes** | **Integer** | Decoded image size in bytes. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::BrowserScreenshotResult.new(
  url: null,
  format: null,
  image_base64: null,
  size_bytes: null
)
```

