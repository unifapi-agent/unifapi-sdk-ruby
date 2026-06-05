# Unifapi::SeoBacklinksTimeseriesRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Domain, subdomain, or page to analyze. A domain or subdomain is specified without https:// and www. (example.com); a page is specified as an absolute URL (https://example.com/blog/). |  |
| **date_from** | **String** | Start date (yyyy-mm-dd) for the series. Minimum 2019-01-30; defaults to one month ago. | [optional] |
| **date_to** | **String** | End date (yyyy-mm-dd). Defaults to today. | [optional] |
| **group_range** | **String** | Granularity used to group the series. Defaults to month. | [optional] |
| **include_subdomains** | **Boolean** | Include backlinks pointing to the target&#39;s subdomains. Defaults to true. | [optional] |
| **rank_scale** | [**SeoBacklinksRankScale**](SeoBacklinksRankScale.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksTimeseriesRequest.new(
  target: null,
  date_from: null,
  date_to: null,
  group_range: null,
  include_subdomains: null,
  rank_scale: null
)
```

