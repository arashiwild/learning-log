# Design Pattern: Factory

Factory pattern menyembunyikan logika pembuatan object di balik satu fungsi/method.

```js
function createShape(type) {
  if (type === 'circle') return new Circle();
  if (type === 'square') return new Square();
}
```

Memudahkan penambahan jenis object baru tanpa mengubah kode pemanggil.
