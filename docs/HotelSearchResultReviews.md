# Unifapi::HotelSearchResultReviews

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **rating** | **Float** | Aggregate guest rating, typically on a 0-5 scale. | [optional] |
| **votes_count** | **Integer** | Number of guest votes behind the rating. | [optional] |
| **rating_distribution** | **Hash&lt;String, Float&gt;** | Vote counts keyed by star rating (\&quot;1\&quot;-\&quot;5\&quot;) when present. | [optional] |
| **extras** | **Hash** |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::HotelSearchResultReviews.new(
  rating: null,
  votes_count: null,
  rating_distribution: null,
  extras: null
)
```

