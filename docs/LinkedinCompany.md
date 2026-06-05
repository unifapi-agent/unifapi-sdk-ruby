# Unifapi::LinkedinCompany

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | URL slug (LinkedIn&#39;s &#x60;universal_name&#x60;). Use this for every /linkedin/companies/{id}/... endpoint. |  |
| **company_id** | **String** | Numeric LinkedIn-internal id. Exposed because LinkedIn pages and ad-library URLs reference it; not needed for any /linkedin/* call. |  |
| **name** | **String** |  |  |
| **description** | **String** |  |  |
| **website_url** | **String** |  |  |
| **linkedin_url** | **String** |  |  |
| **is_verified** | **Boolean** |  |  |
| **is_active** | **Boolean** |  |  |
| **follower_count** | **Integer** |  |  |
| **employee_count** | **Integer** |  |  |
| **employee_count_range** | [**LinkedinEmployeeCountRange**](LinkedinEmployeeCountRange.md) |  |  |
| **industries** | **Array&lt;String&gt;** |  |  |
| **specialities** | **Array&lt;String&gt;** |  |  |
| **headquarters** | [**LinkedinHeadquarters**](LinkedinHeadquarters.md) |  |  |
| **logo_url** | **String** |  |  |
| **cover_image_url** | **String** |  |  |
| **hashtags** | [**Array&lt;LinkedinCompanyHashtagsInner&gt;**](LinkedinCompanyHashtagsInner.md) |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::LinkedinCompany.new(
  id: null,
  company_id: null,
  name: null,
  description: null,
  website_url: null,
  linkedin_url: null,
  is_verified: null,
  is_active: null,
  follower_count: null,
  employee_count: null,
  employee_count_range: null,
  industries: null,
  specialities: null,
  headquarters: null,
  logo_url: null,
  cover_image_url: null,
  hashtags: null
)
```

