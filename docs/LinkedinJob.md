# Unifapi::LinkedinJob

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **title** | **String** |  |  |
| **description** | **String** |  |  |
| **job_url** | **String** |  |  |
| **location** | **String** |  |  |
| **location_geocode** | **String** |  |  |
| **country_code** | **String** |  |  |
| **state** | **String** |  |  |
| **level** | **String** |  |  |
| **employment_type** | **String** |  |  |
| **is_new** | **Boolean** |  |  |
| **view_count** | **Integer** |  |  |
| **apply_count** | **Integer** |  |  |
| **salary** | [**LinkedinJobSalary**](LinkedinJobSalary.md) |  |  |
| **is_remote_allowed** | **Boolean** |  |  |
| **listed_at** | **String** |  |  |
| **original_listed_at** | **String** |  |  |
| **expire_at** | **String** |  |  |
| **industries** | **Array&lt;String&gt;** |  |  |
| **job_functions** | **Array&lt;String&gt;** |  |  |
| **benefits** | **Array&lt;String&gt;** |  |  |
| **workplace_types** | **Array&lt;String&gt;** |  |  |
| **company** | [**LinkedinJobCompany**](LinkedinJobCompany.md) |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::LinkedinJob.new(
  id: null,
  title: null,
  description: null,
  job_url: null,
  location: null,
  location_geocode: null,
  country_code: null,
  state: null,
  level: null,
  employment_type: null,
  is_new: null,
  view_count: null,
  apply_count: null,
  salary: null,
  is_remote_allowed: null,
  listed_at: null,
  original_listed_at: null,
  expire_at: null,
  industries: null,
  job_functions: null,
  benefits: null,
  workplace_types: null,
  company: null
)
```

