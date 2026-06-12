# Error Handling Best Practices

- Tangkap error sedekat mungkin dengan sumbernya
- Gunakan custom error class untuk kategori error berbeda
- Jangan menelan error secara diam-diam (silent fail)
- Log error dengan konteks yang cukup (request id, user id, dll)
- Berikan pesan error yang jelas tapi tidak membocorkan detail sensitif ke user
