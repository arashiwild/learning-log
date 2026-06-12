# OAuth Dasar

OAuth adalah protokol otorisasi yang memungkinkan aplikasi mengakses resource user tanpa perlu password.

Flow umum (Authorization Code):
1. User diarahkan ke provider (misal Google) untuk login
2. Provider redirect kembali dengan authorization code
3. Aplikasi menukar code dengan access token
4. Access token digunakan untuk mengakses API
