# Ducentrace

A middleware to trace the request and response on an express server

```js
const app = require('express')();
const ducentrace = require('ducentrace');

app.use(ducentrace());
app.listen(80, () => {
	console.log('Server listening on port 80');
});
```

Author: **duccem29**
