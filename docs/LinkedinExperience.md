# Unifapi::LinkedinExperience

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **title** | **String** |  |  |
| **description** | **String** |  |  |
| **location** | **String** |  |  |
| **employment_type** | **String** |  |  |
| **date** | [**LinkedinDateRange**](LinkedinDateRange.md) |  |  |
| **company** | [**LinkedinCompanyRef**](LinkedinCompanyRef.md) |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::LinkedinExperience.new(
  title: null,
  description: null,
  location: null,
  employment_type: null,
  date: null,
  company: null
)
```

