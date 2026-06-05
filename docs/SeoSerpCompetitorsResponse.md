# Unifapi::SeoSerpCompetitorsResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **keywords** | **Array&lt;String&gt;** | Seed keywords echoed from the request. |  |
| **location** | **String** |  |  |
| **language** | **String** |  |  |
| **total_count** | **Integer** | Total number of competing domains available in DataForSEO&#39;s database. | [optional] |
| **results** | [**Array&lt;SeoSerpCompetitorItem&gt;**](SeoSerpCompetitorItem.md) | Domains competing for the seed keywords, ranked by visibility. Each domain is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoSerpCompetitorsResponse.new(
  keywords: null,
  location: null,
  language: null,
  total_count: null,
  results: null
)
```

