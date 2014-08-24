java-modern-libraries
=====================

A list of modern Java libraries.

Template
---

- [Jade4J](https://github.com/neuland/jade4j)

```jade
!!! 5
html
  head
    title= pageName
  body
    ol#books
      for book in books
        if book.available
          li #{book.name} for #{book.price} €
```
