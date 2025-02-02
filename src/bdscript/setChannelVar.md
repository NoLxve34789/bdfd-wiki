# $setChannelVar
Updates a variable's value for a channel.

## Syntax
```
$setChannelVar[Variable Name;New Value;(Channel ID)]
```

### Parameters
- `Variable Name` `(Type: String || Flag: Required)`: The variable to update.
- `New Value` `(Type: String || Flag: Emptiable)`: The new variable value.
- `Channel ID` `(Type: Snowflake || Flag: Optional)`: The channel to assign the new value to. If no 'Channel ID' is present, the current channel will be used.

> 📌 Channel variables value has a max character limit of 499 (4999, if premium).

[See more in the Variables guide...](../guides/introduction/variables.md)
