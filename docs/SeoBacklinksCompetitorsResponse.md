# Unifapi::SeoBacklinksCompetitorsResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Target echoed from the request. |  |
| **total_count** | **Integer** | Total number of competitors available in DataForSEO&#39;s database. | [optional] |
| **results** | [**Array&lt;SeoBacklinksCompetitorItem&gt;**](SeoBacklinksCompetitorItem.md) | Domains that share referring domains with the target, by shared-domain count. Each competitor is one billable record. |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksCompetitorsResponse.new(
  target: null,
  total_count: null,
  results: null
)
```

