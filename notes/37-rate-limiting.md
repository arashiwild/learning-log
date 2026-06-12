# Rate Limiting

Membatasi jumlah request dari client dalam periode waktu tertentu untuk mencegah abuse.

Strategi umum:
- Fixed window
- Sliding window
- Token bucket
- Leaky bucket

Biasanya direspon dengan HTTP 429 Too Many Requests.
