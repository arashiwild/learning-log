# JavaScript Array Methods

## map()
Membuat array baru dengan hasil transformasi setiap elemen.
```js
[1,2,3].map(x => x * 2) // [2,4,6]
```

## filter()
Membuat array baru berisi elemen yang lolos kondisi.
```js
[1,2,3,4].filter(x => x % 2 === 0) // [2,4]
```

## reduce()
Mengakumulasi array menjadi satu nilai.
```js
[1,2,3].reduce((a,b) => a + b, 0) // 6
```
