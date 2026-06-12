# API Rate Limit Handling (Client Side)

Saat menerima HTTP 429:
- Baca header `Retry-After` jika tersedia
- Implementasikan exponential backoff dengan jitter
- Batasi jumlah retry agar tidak infinite loop
- Pertimbangkan request queue/throttling di sisi client untuk menghindari rate limit sejak awal
