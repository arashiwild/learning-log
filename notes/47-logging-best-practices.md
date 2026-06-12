# Logging Best Practices

- Gunakan level log yang jelas: debug, info, warn, error
- Sertakan konteks (request id, user id, timestamp)
- Hindari logging data sensitif (password, token, kartu kredit)
- Gunakan format terstruktur (JSON) agar mudah di-parse tools monitoring
- Pastikan log tidak membanjiri storage — atur retention policy
