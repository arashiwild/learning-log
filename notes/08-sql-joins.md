# SQL JOIN Types

- INNER JOIN: hanya baris yang cocok di kedua tabel
- LEFT JOIN: semua baris tabel kiri + yang cocok di kanan
- RIGHT JOIN: semua baris tabel kanan + yang cocok di kiri
- FULL OUTER JOIN: semua baris dari kedua tabel

```sql
SELECT * FROM orders
LEFT JOIN customers ON orders.customer_id = customers.id;
```
