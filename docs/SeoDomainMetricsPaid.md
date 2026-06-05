# Unifapi::SeoDomainMetricsPaid

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **count** | **Integer** | Number of keywords the domain ranks for in this result type. | [optional] |
| **etv** | **Float** | Estimated monthly organic traffic (clicks) from this result type. | [optional] |
| **estimated_paid_traffic_cost** | **Float** | Estimated monthly cost (USD) of buying this traffic through ads. | [optional] |
| **pos_1** | **Integer** | Keywords ranking in position 1. | [optional] |
| **pos_2_3** | **Integer** | Keywords ranking in positions 2-3. | [optional] |
| **pos_4_10** | **Integer** | Keywords ranking in positions 4-10. | [optional] |
| **pos_11_20** | **Integer** | Keywords ranking in positions 11-20. | [optional] |
| **pos_21_30** | **Integer** | Keywords ranking in positions 21-30. | [optional] |
| **pos_31_40** | **Integer** | Keywords ranking in positions 31-40. | [optional] |
| **pos_41_50** | **Integer** | Keywords ranking in positions 41-50. | [optional] |
| **pos_51_60** | **Integer** | Keywords ranking in positions 51-60. | [optional] |
| **pos_61_70** | **Integer** | Keywords ranking in positions 61-70. | [optional] |
| **pos_71_80** | **Integer** | Keywords ranking in positions 71-80. | [optional] |
| **pos_81_90** | **Integer** | Keywords ranking in positions 81-90. | [optional] |
| **pos_91_100** | **Integer** | Keywords ranking in positions 91-100. | [optional] |
| **is_new** | **Integer** | Keywords newly ranking since the last check. | [optional] |
| **is_up** | **Integer** | Keywords that moved up since the last check. | [optional] |
| **is_down** | **Integer** | Keywords that moved down since the last check. | [optional] |
| **is_lost** | **Integer** | Keywords lost since the last check. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoDomainMetricsPaid.new(
  count: null,
  etv: null,
  estimated_paid_traffic_cost: null,
  pos_1: null,
  pos_2_3: null,
  pos_4_10: null,
  pos_11_20: null,
  pos_21_30: null,
  pos_31_40: null,
  pos_41_50: null,
  pos_51_60: null,
  pos_61_70: null,
  pos_71_80: null,
  pos_81_90: null,
  pos_91_100: null,
  is_new: null,
  is_up: null,
  is_down: null,
  is_lost: null
)
```

