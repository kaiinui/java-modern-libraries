java-modern-libraries
=====================

A list of modern Java libraries.

Supports
---

- [Guava](https://code.google.com/p/guava-libraries/) - Here's what Java is missing!

Utilities
---

- [Joda-Time](http://www.joda.org/joda-time/) - DateTime made easy.

```java
DateTime dt = new DateTime("2013-08-01T12:30:50")

dt.dayOfMonth().getMaximumValue();
```

- [Jackson](http://jackson.codehaus.org/) - High performance JSON processor

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

