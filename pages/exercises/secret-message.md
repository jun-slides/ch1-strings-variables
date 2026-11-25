---
layout: quote
---

# Exercise: Create a secret message


Replace a with @ and e with 3 to make the message appear secret.



<div v-click>
  <iframe
    v-if="$clicks >= 1"
    src="https://trinket.strivemath.org/embed/python3/0e69c99a9430?outputOnly=true&runOption=run&start=result"
    class="w-full h-80 rounded-lg border border-gray-500/40 mt-6"
  ></iframe>
</div>



---
layout: quote
---

# Instructions

<v-clicks>

- Use replace method to replace a with @ and e with 3 
- The challenge is to figure out how to replace two things.

</v-clicks>


---
layout: quote
---

# Starting Code

```python
message = input("Enter a message: ")

# Step 1 replace a with @

# Step 2 replace e with 3

# Step 3 print the encoded message
```


---
layout: quote
---

# Wrong Solution

````md magic-move {lines:true}
```python {*|1}
message = input("Enter a message: ")

result = message.replace("a", "@")
result = message.replace("e", "3")

print(f"Encoded message: {result}")
```

```python {1}
message = "Have a great day"

result = message.replace("a", "@")
result = message.replace("e", "3")

print(f"Encoded message: {result}")
```

```python {3}
message = "Have a great day"

result = message.replace("a", "@")
result = message.replace("e", "3")

print(f"Encoded message: {result}")
```

```python {3}
message = "Have a great day"

result = "Have a great day".replace("a", "@")
result = message.replace("e", "3")

print(f"Encoded message: {result}")
```

```python {3}
message = "Have a great day"

result = "H@ve @ gre@t d@y"
result = message.replace("e", "3")

print(f"Encoded message: {result}")
```

```python {4}
message = "Have a great day"

result = "H@ve @ gre@t d@y"
result = message.replace("e", "3")

print(f"Encoded message: {result}")
```

```python {4}
message = "Have a great day"

result = "H@ve @ gre@t d@y"
result = "Have a great day".replace("e", "3")

print(f"Encoded message: {result}")
```

```python {4}
message = "Have a great day"

result = "H@ve @ gre@t d@y"
result = "Hav3 a gr3at day"

print(f"Encoded message: {result}")
```


```python {6}
message = "Have a great day"

result = "H@ve @ gre@t d@y"
result = "Hav3 a gr3at day"

print(f"Encoded message: {result}")
```

```python {6}
message = "Have a great day"

result = "H@ve @ gre@t d@y"
result = "Hav3 a gr3at day"

print("Encoded message: Hav3 a gr3at day")
```
````


---
layout: quote
---

# Correct Solution 1

````md magic-move {lines:true}
```python {*|1}
message = input("Enter a message: ")

secret = message.replace("a", "@")
secret = secret.replace("e", "3")

print(f"Encoded message: {secret}")
```

```python {1|3}
message = "Have a great day"

secret = message.replace("a", "@")
secret = secret.replace("e", "3")

print(f"Encoded message: {secret}")
```


```python {3}
message = "Have a great day"

secret = "Have a great day".replace("a", "@")
secret = secret.replace("e", "3")

print(f"Encoded message: {secret}")
```

```python {3|4}
message = "Have a great day"

secret = "H@ve a gre@t d@y"
secret = secret.replace("e", "3")

print(f"Encoded message: {secret}")
```

```python {4}
message = "Have a great day"

secret = "H@ve a gre@t d@y"
secret = "H@ve a gre@t d@y".replace("e", "3")

print(f"Encoded message: {secret}")
```

```python {4|6}
message = "Have a great day"

secret = "H@ve a gre@t d@y"
secret = "H@v3 a gr3@t d@y"

print(f"Encoded message: {secret}")
```

```python {6}
message = "Have a great day"

secret = "H@ve a gre@t d@y"
secret = "H@v3 a gr3@t d@y"

print("Encoded message: H@v3 a gr3@t d@y")
```

````


---
layout: quote
---

# Correct Solution 2


````md magic-move {lines:true}
```python {*|1}
message = input("Enter a message: ")

secret = message.replace("a", "@").replace("e", "3")

print(f"Encoded message: {secret}")
```

```python {1|3}
message = "I ate a cake"

secret = message.replace("a", "@").replace("e", "3")

print(f"Encoded message: {secret}")
```

```python {3}
message = "I ate a cake"

secret = "I ate a cake".replace("a", "@").replace("e", "3")

print(f"Encoded message: {secret}")
```

```python {3}
message = "I ate a cake"

secret = "I @te @ c@ke".replace("e", "3")

print(f"Encoded message: {secret}")
```

```python {3|5}
message = "I ate a cake"

secret = "I @t3 @ c@k3"

print(f"Encoded message: {secret}")
```

```python {5}
message = "I ate a cake"

secret = "I @t3 @ c@k3"

print("Encoded message: I @t3 @ c@k3")
```
````