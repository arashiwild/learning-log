# WebSocket Dasar

WebSocket menyediakan koneksi dua arah (full-duplex) antara client dan server yang tetap terbuka, cocok untuk chat real-time, notifikasi, atau game online.

```js
const ws = new WebSocket('wss://example.com/socket');
ws.onmessage = (event) => console.log(event.data);
ws.send('hello');
```
