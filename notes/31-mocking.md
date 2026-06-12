# Mocking di Testing

Mocking digunakan untuk mengganti dependency eksternal (API, database) dengan object tiruan saat testing.

```js
jest.mock('./api');
api.getData.mockResolvedValue({ id: 1 });
```

Membuat test lebih cepat, stabil, dan tidak bergantung pada layanan eksternal.
