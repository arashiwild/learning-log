# Database Indexing

Index mempercepat pencarian data dengan struktur seperti B-tree, tapi memperlambat write (insert/update/delete) karena index juga harus diperbarui.

```sql
CREATE INDEX idx_users_email ON users(email);
```

Gunakan index pada kolom yang sering dipakai di WHERE, JOIN, atau ORDER BY.
