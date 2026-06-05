# Unifapi::SeoBacklinksCompetitorItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Competing domain that shares part of the target&#39;s backlink profile. |  |
| **rank** | **Integer** | Backlink rank of the competing domain (0-1000 by default). | [optional] |
| **intersections** | **Integer** | Number of referring domains the competitor shares with the target. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksCompetitorItem.new(
  target: null,
  rank: null,
  intersections: null
)
```

