# JWT Authentication

JSON Web Token terdiri dari 3 bagian: header, payload, signature, dipisahkan titik.

Flow umum:
1. User login, server membuat JWT
2. Token dikirim ke client, disimpan (misal di cookie/localStorage)
3. Setiap request, client mengirim token di header Authorization
4. Server verifikasi signature token
