# AzureAIClient::CompletionsCreate200ResponseChoicesInnerLogprobs

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **tokens** | **Array&lt;String&gt;** |  | [optional] |
| **token_logprobs** | **Array&lt;Float&gt;** |  | [optional] |
| **top_logprobs** | **Array&lt;Hash&lt;String, Float&gt;&gt;** |  | [optional] |
| **text_offset** | **Array&lt;Integer&gt;** |  | [optional] |

## Example

```ruby
require 'azureai_client'

instance = AzureAIClient::CompletionsCreate200ResponseChoicesInnerLogprobs.new(
  tokens: null,
  token_logprobs: null,
  top_logprobs: null,
  text_offset: null
)
```

