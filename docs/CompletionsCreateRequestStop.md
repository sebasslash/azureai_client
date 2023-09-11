# AzureAIClient::CompletionsCreateRequestStop

## Class instance methods

### `openapi_one_of`

Returns the list of classes defined in oneOf.

#### Example

```ruby
require 'azureai_client'

AzureAIClient::CompletionsCreateRequestStop.openapi_one_of
# =>
# [
#   :'Array<String>',
#   :'String'
# ]
```

### build

Find the appropriate object from the `openapi_one_of` list and casts the data into it.

#### Example

```ruby
require 'azureai_client'

AzureAIClient::CompletionsCreateRequestStop.build(data)
# => #<Array<String>:0x00007fdd4aab02a0>

AzureAIClient::CompletionsCreateRequestStop.build(data_that_doesnt_match)
# => nil
```

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **data** | **Mixed** | data to be matched against the list of oneOf items |

#### Return type

- `Array<String>`
- `String`
- `nil` (if no type matches)

