# Unifapi::XUser

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **name** | **String** |  |  |
| **username** | **String** |  |  |
| **created_at** | **String** |  | [optional] |
| **description** | **String** |  | [optional] |
| **location** | **String** |  | [optional] |
| **url** | **String** |  | [optional] |
| **profile_image_url** | **String** |  | [optional] |
| **profile_banner_url** | **String** |  | [optional] |
| **protected** | **Boolean** |  | [optional] |
| **verified** | **Boolean** |  | [optional] |
| **verified_type** | **String** |  | [optional] |
| **pinned_tweet_id** | **String** |  | [optional] |
| **public_metrics** | [**XPublicMetrics**](XPublicMetrics.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::XUser.new(
  id: null,
  name: null,
  username: null,
  created_at: null,
  description: null,
  location: null,
  url: null,
  profile_image_url: null,
  profile_banner_url: null,
  protected: null,
  verified: null,
  verified_type: null,
  pinned_tweet_id: null,
  public_metrics: null
)
```

