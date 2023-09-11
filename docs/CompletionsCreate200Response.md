# AzureAIClient::CompletionsCreate200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** |  |  |
| **object** | **String** |  |  |
| **created** | **Integer** |  |  |
| **model** | **String** |  |  |
| **choices** | [**Array&lt;CompletionsCreate200ResponseChoicesInner&gt;**](CompletionsCreate200ResponseChoicesInner.md) |  |  |
| **usage** | [**CompletionsCreate200ResponseUsage**](CompletionsCreate200ResponseUsage.md) |  | [optional] |

## Example

```ruby
require 'azureai_client'

instance = AzureAIClient::CompletionsCreate200Response.new(
  id: null,
  object: null,
  created: null,
  model: null,
  choices: null,
  usage: null
)
```

