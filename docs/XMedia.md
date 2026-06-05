# Unifapi::XMedia

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **media_key** | **String** |  | [optional] |
| **type** | **String** |  |  |
| **url** | **String** |  | [optional] |
| **preview_image_url** | **String** |  | [optional] |
| **height** | **Float** |  | [optional] |
| **width** | **Float** |  | [optional] |
| **duration_ms** | **Float** |  | [optional] |
| **variants** | [**Array&lt;XMediaVariantsInner&gt;**](XMediaVariantsInner.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::XMedia.new(
  media_key: null,
  type: null,
  url: null,
  preview_image_url: null,
  height: null,
  width: null,
  duration_ms: null,
  variants: null
)
```

