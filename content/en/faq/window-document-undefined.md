
This is due to the server-side rendering. If you need to specify that you want to import a resource only on the client-side, you need to use the `process.client` variable.

For example, in your `.vue` file:

```js
if (process.client) {
  require('external_library')
}
```
