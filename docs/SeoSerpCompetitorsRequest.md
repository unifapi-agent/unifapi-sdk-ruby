# Unifapi::SeoSerpCompetitorsRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **keywords** | **Array&lt;String&gt;** | Seed keywords (1-200). Returns the domains that rank for them. |  |
| **location** | [**SeoSerpCompetitorsLocation**](SeoSerpCompetitorsLocation.md) |  | [optional] |
| **language** | **String** | Search language as an ISO code or full language name. Defaults to en. | [optional] |
| **include_subdomains** | **Boolean** | When true (default), count subdomain rankings toward each domain. | [optional] |
| **limit** | **Integer** | Maximum number of competing domains to return. Defaults to 100. | [optional] |
| **offset** | **Integer** | Number of domains to skip from the start of the results. | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoSerpCompetitorsRequest.new(
  keywords: null,
  location: null,
  language: null,
  include_subdomains: null,
  limit: null,
  offset: null
)
```

