# Python List Comprehension

List comprehension adalah cara singkat membuat list dari iterable.

```python
squares = [x**2 for x in range(10)]
even = [x for x in range(20) if x % 2 == 0]
```

Lebih cepat dan ringkas dibanding loop biasa untuk transformasi sederhana.
