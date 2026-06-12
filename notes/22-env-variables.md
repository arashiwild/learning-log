# Environment Variables & .env

Environment variables menyimpan konfigurasi sensitif (API key, DB URL) di luar kode.

```
# .env
DATABASE_URL=postgres://user:pass@localhost/db
API_KEY=secret123
```

Jangan commit file .env ke repo publik — gunakan .gitignore.
