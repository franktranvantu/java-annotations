# The @SuppressWarnings Annotation - "static"

Here we get our first look at the @SuppressWarnings annotation. This annotation can be used to turn off compiler warnings - either all warnings or only certain ones. 

This section considers the warning a compiler gives you when you incorrectly call a static method.

```bash
javac -Xlint -d out -cp src src/com/franktran/suppresswarnings/Main.java
```