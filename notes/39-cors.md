# CORS dan Cara Mengatasinya

CORS (Cross-Origin Resource Sharing) adalah mekanisme browser yang membatasi request dari origin berbeda.

Cara mengatasi di server (contoh Express):
```js
app.use((req, res, next) => {
  res.header('Access-Control-Allow-Origin', '*');
  res.header('Access-Control-Allow-Headers', 'Content-Type');
  next();
});
```
