---
layout: quote
---

# String Methods

Strings have built-in tricks called **methods**. Here are the most useful ones:

### Uppercase, Lowercase and Titlecase


````md magic-move {lines:true}
```python 
name = "MUHammad jUNAid"

name.upper()  # MUHAMMAD JUNAID
name.lower()  # muhammad junaid
name.title()  # Muhammad Junaid
```

```python {*|1,3}
name = "MUHammad jUNAid"

name.upper()  
name.lower()  
name.title()  
```

```python {1,3}
name = "MUHammad jUNAid"

"MUHammad jUNAid".upper()  
name.lower()  
name.title()  
```

```python {1,3|1,4}
name = "MUHammad jUNAid"

"MUHAMMAD JUNAID" 
name.lower()  
name.title()  
```

```python {1,4}
name = "MUHammad jUNAid"

"MUHAMMAD JUNAID" 
"MUHammad jUNAid".lower()  
name.title()  
```


```python {1,4|1,5}
name = "MUHammad jUNAid"

"MUHAMMAD JUNAID"
"muhammad junid"
name.title()  
```

```python {1,5}
name = "MUHammad jUNAid"

"MUHAMMAD JUNAID"
"muhammad junid"
"MUHammad jUNAid".title()  
```

```python {1,5|*}
name = "MUHammad jUNAid"

"MUHAMMAD JUNAID"
"muhammad junid"
"Muhammad Junaid"
```

```python 
name = "MUHammad jUNAid"

name.upper()  # MUHAMMAD JUNAID
name.lower()  # muhammad junaid
name.title()  # Muhammad Junaid
```
````

---
layout: quote
---

# Replace Text

```python
message = "I like cats"
message.replace("cat", "dog")  # I like dogs
```