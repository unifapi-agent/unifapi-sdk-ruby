# Unifapi::TwitterRelationship

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **source_id** | **String** |  | [optional] |
| **source_username** | **String** |  | [optional] |
| **target_id** | **String** |  | [optional] |
| **target_username** | **String** |  | [optional] |
| **following** | **Boolean** |  | [optional] |
| **followed_by** | **Boolean** |  | [optional] |
| **raw** | **Object** |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::TwitterRelationship.new(
  source_id: null,
  source_username: null,
  target_id: null,
  target_username: null,
  following: null,
  followed_by: null,
  raw: null
)
```

