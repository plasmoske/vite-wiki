# TestApi

:::tip Maintainer
[TiantaoZhu](https://github.com/TiantaoZhu)
:::

## testapi_getTestToken
Acquire Vite testing tokens. This method will send 1-1001 random VTT to the address.

- **Parameters**: 
`toAddress`: `address` - The account address to receive test tokens

- **return**:

1. `string`:`bigint` - The amount of test tokens that have been sent
2. `error`: Error message
