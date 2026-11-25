---
layout: quote
---

# Subscripting: Accessing Individual Characters

You can pull out specific characters using square brackets `[]`:


<v-clicks>

````md magic-move {lines:true}
```python
msg = "Hello"
msg[0]   # H (first character)
msg[1]   # e (second character)
msg[4]   # o (last character)
```

```python
msg = "Hello"
"Hello"[0]   
"Hello"[1]   
"Hello"[4]   
```


```python
msg = "Hello"
"H"  
"e"   
"o"  
```

```python
msg = "Hello"
msg[0]   # H (first character)
msg[1]   # e (second character)
msg[4]   # o (last character)
```
````

**Remember:** Programmers count from 0, not 1!

```
H  e  l  l  o
0  1  2  3  4
```

[TRY IT] What does `"Python"[2]` return?

</v-clicks>
