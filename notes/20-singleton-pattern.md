# Design Pattern: Singleton

Memastikan hanya ada satu instance dari sebuah class.

```js
class Database {
  static instance;
  constructor() {
    if (Database.instance) return Database.instance;
    Database.instance = this;
  }
}
```

Sering digunakan untuk koneksi database atau konfigurasi global.
