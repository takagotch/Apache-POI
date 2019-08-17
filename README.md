### apache-poi
---
https://github.com/apache/poi

https://poi.apache.org/

```java
// src/java/org/apache/poi/EmptyFileException.java
package org.apache.poi;

public class EmptyFileException extends IllegalArgumentException {
  private static final long serialVersionUID = xxxL;
  
  public EmptyFileException() {
    super("The supplied file was empty (zero bytes long)");
  }
}
```

```sh
ant jar
```

```
```
