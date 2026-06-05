# Unifapi::LinkedinJobListing

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **title** | **String** |  |  |
| **job_url** | **String** |  |  |
| **listed_at** | **String** |  |  |
| **is_promoted** | **Boolean** |  |  |
| **is_easy_apply** | **Boolean** |  |  |
| **location** | **String** |  |  |
| **company** | [**LinkedinJobListingCompany**](LinkedinJobListingCompany.md) |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::LinkedinJobListing.new(
  id: null,
  title: null,
  job_url: null,
  listed_at: null,
  is_promoted: null,
  is_easy_apply: null,
  location: null,
  company: null
)
```

