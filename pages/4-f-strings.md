---
layout: quote
---

# f-strings - Mixing Text and Variables

<v-clicks>

To include variables inside text, use **f-strings**:

```` md magic-move {lines: true}
```python {*|1|2}
name = "Sarah"
print(f"Hello, {name}!")
```

```python {2|*}
name = "Sarah"
print("Hello, Sarah!")
```
````

</v-clicks>


---
layout: quote
---

# f-strings - inserting multiple variables

<v-clicks>

You can insert as many variables as you want inside an f-string

```` md magic-move {lines: true}
```python {*|1-2|3}
name = "Sarah"
city = "London"
print(f"{name} lives in {city}.")
```

```python {3|*}
name = "Sarah"
city = "London"
print("Sarah lives in London.")
```

````
</v-clicks>


