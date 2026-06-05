# Unifapi::SeoBacklinksHistoryRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target** | **String** | Domain, subdomain, or page to analyze. A domain or subdomain is specified without https:// and www. (example.com); a page is specified as an absolute URL (https://example.com/blog/). |  |
| **date_from** | **String** | Start date (yyyy-mm-dd) for the history. Minimum 2019-01-30; defaults to one year ago. | [optional] |
| **date_to** | **String** | End date (yyyy-mm-dd). Defaults to today. | [optional] |
| **rank_scale** | [**SeoBacklinksRankScale**](SeoBacklinksRankScale.md) |  | [optional] |
| **view** | [**SeoBacklinksView**](SeoBacklinksView.md) |  | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinksHistoryRequest.new(
  target: null,
  date_from: null,
  date_to: null,
  rank_scale: null,
  view: null
)
```

