# The @SuppressWarnings Annotation - "fallthrough"

In a switch statement with many cases, it can be easy to accidentally leave off a break statement. 

And in some cases, this may be done intentionally to save a few lines of code. 

We can use the @SuppressWarnings annotation to control the compiler warnings about these scenarios when a break statement is missing and execution "falls through" to the next case.

```bash
javac -Xlint -d out -cp src src/com/franktran/suppresswarnings/Main.java
```