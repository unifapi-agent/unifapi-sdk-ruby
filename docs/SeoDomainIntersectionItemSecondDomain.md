# Unifapi::SeoDomainIntersectionItemSecondDomain

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **rank_group** | **Integer** | Position in SERP grouping organic results together (ignores ads/features). | [optional] |
| **rank_absolute** | **Integer** | Absolute position in SERP counting every element. | [optional] |
| **position** | **String** | Side of the SERP the element appears on: left or right. | [optional] |
| **domain** | **String** | Domain that holds the ranking page. | [optional] |
| **title** | **String** | Title of the ranking page. | [optional] |
| **url** | **String** | URL of the ranking page. | [optional] |
| **etv** | **Float** | Estimated monthly traffic the keyword sends to this URL. | [optional] |
| **estimated_paid_traffic_cost** | **Float** | Estimated monthly ad cost (USD) of the traffic this URL receives. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoDomainIntersectionItemSecondDomain.new(
  rank_group: null,
  rank_absolute: null,
  position: null,
  domain: null,
  title: null,
  url: null,
  etv: null,
  estimated_paid_traffic_cost: null
)
```

