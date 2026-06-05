# Unifapi::SeoBacklinksBulkSpamScoreItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Domain, subdomain, or page echoed from the request. |  |
| **spam_score** | **Integer** | Spam score of the target, 0-100. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksBulkSpamScoreItem.new(
  target: null,
  spam_score: null
)
```

