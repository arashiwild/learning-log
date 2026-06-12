# Caching Strategies

- **Cache-aside**: aplikasi cek cache dulu, kalau miss baru query DB dan simpan ke cache
- **Write-through**: setiap write juga langsung update cache
- **Write-back**: write ke cache dulu, sinkron ke DB belakangan
- **TTL (Time To Live)**: cache otomatis expired setelah waktu tertentu

Tools umum: Redis, Memcached.
