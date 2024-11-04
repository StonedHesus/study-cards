How do you `define` a `record`?
---
A `record` is defined using the `record` `keyword`, much like a `class`, though unlike one, a `record` has a list of its `attributes/fields` `after the name`, like so:

```java
public record Person(String name, Integer age) {}  
```