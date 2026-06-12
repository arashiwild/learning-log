# TypeScript Basics

TypeScript menambahkan static typing ke JavaScript.

```ts
interface User {
  id: number;
  name: string;
  email?: string; // optional
}

function greet(user: User): string {
  return `Hello, ${user.name}`;
}
```

Membantu menangkap error di compile time sebelum runtime.
