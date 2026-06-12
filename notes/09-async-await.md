# Async/Await di JavaScript

async/await adalah syntax sugar di atas Promise agar kode asynchronous terlihat synchronous.

```js
async function getData() {
  try {
    const res = await fetch('/api/data');
    const data = await res.json();
    return data;
  } catch (err) {
    console.error(err);
  }
}
```
