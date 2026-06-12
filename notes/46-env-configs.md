# Environment Configs (dev/staging/prod)

Setiap environment punya konfigurasi berbeda (DB, API key, log level).

Contoh struktur:
```
.env.development
.env.staging
.env.production
```

Pastikan tidak ada konfigurasi production yang ter-hardcode di kode, gunakan environment variables atau config service.
