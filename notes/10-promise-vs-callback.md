# Promise vs Callback

## Callback
Fungsi yang dipanggil setelah operasi selesai, rawan 'callback hell'.

## Promise
Object yang merepresentasikan hasil operasi async di masa depan, punya state: pending, fulfilled, rejected.

```js
fetch('/api').then(res => res.json()).catch(err => console.error(err));
```

Promise lebih mudah dibaca dan di-chain dibanding nested callback.
