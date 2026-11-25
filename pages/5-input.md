---
layout: quote
---

# Getting User Input

Instead of hardcoding values, let's ask the user:

<v-click>

```python {lines:true}
name = input("What's your name? ")
print(f"Hello, {name}!")
```

</v-click>

<v-click>

[CHALLENGE]: add another input call asking where they live.

</v-click>


---
layout: quote
---

# Adding another input

````md magic-move {lines:true}
```python 
name = input("What's your name? ")
print(f"Nice to meet you, {name}!")
```

```python
name = input("What's your name? ")
city = input("Where do you live? ")
print(f"Nice to meet you, {name}!")
```

```python
name = input("What's your name? ")
city = input("Where do you live? ")
print(f"Nice to meet you, {name} from {city}!")
```

````


