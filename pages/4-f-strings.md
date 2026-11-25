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

```python 
name = "Sarah"
print(f"Hello, {name}!")   # Output: Hello, Sarah!
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



---
layout: quote
---

# Simple f-string exercises

<v-click>

1. Create a variable for your name and a variable for your age. Print this sentence using an f-string:

```
My name is Charlie and I am 25 years old.
```

</v-click>

<v-click>


2. Create a variable for a city and a variable for a country. Print:

```
London is in England.
```

</v-click>


<v-click>


3. Create variables for a product name and its price. Print:

```
A cup of coffee costs $3.5.
```

</v-click>


<v-click>


4. Create three variables — first name, last name, and job title. Print them all in one sentence:

```
John Smith works as a teacher.
```

</v-click>
