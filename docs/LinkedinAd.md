# Unifapi::LinkedinAd

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **content** | **String** |  |  |
| **ad_url** | **String** |  |  |
| **image_url** | **String** |  |  |
| **ad_type** | **String** |  |  |
| **paid_for_by** | **String** |  |  |
| **advertiser** | [**LinkedinAdAdvertiser**](LinkedinAdAdvertiser.md) |  |  |
| **publisher** | [**LinkedinAdAdvertiser**](LinkedinAdAdvertiser.md) |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::LinkedinAd.new(
  id: null,
  content: null,
  ad_url: null,
  image_url: null,
  ad_type: null,
  paid_for_by: null,
  advertiser: null,
  publisher: null
)
```

