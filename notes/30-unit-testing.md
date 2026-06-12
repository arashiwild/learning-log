# Unit Testing Dasar

Unit test menguji bagian terkecil dari kode (fungsi/method) secara terisolasi.

```js
test('adds 1 + 2 to equal 3', () => {
  expect(sum(1, 2)).toBe(3);
});
```

Tujuan: memastikan setiap unit kode berperilaku sesuai harapan dan mencegah regresi.
