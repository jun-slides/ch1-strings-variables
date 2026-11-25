---
layout: quote
---

# Example 3: Username Generator

<v-clicks>

 Takes a name and creates different username styles using upper/lower.

<iframe
  src="https://trinket.strivemath.org/embed/python3/c2b2781d8151?outputOnly=true&runOption=run&start=result"
  class="w-full h-80 rounded-lg border border-gray-500/40 mt-6"
></iframe>

</v-clicks>

---
layout: quote
---

# Instructions

<v-clicks>

1. Ask for the user's name
2. Print it in UPPERCASE (for shouting style)
3. Print it in lowercase (for username style)
4. Print a formatted message showing both

</v-clicks>


---
layout: quote
---

# Starting Code

```python
# Step 1: Ask for the user's name

# Step 2: Make it in UPPERCASE (for shouting style)

# Step 3: Make it in lowercase (for username style)

# Step 4: Create gamer tag: username + _player

# Step 5: Print a formatted message showing all three

```


---
layout: quote
---

# Solution

````md magic-move
```python
# Step 1: Ask for the user's name

# Step 2: Make it in UPPERCASE (for shouting style)

# Step 3: Make it in lowercase (for username style)

# Step 4: Create gamer tag: username + _player

# Step 5: Print a formatted message showing all three
```


```python
# Step 1: Ask for the user's name
name = input("Enter your name: ")

# Step 2: Make it in UPPERCASE (for shouting style)

# Step 3: Make it in lowercase (for username style)

# Step 4: Create gamer tag: username + _player

# Step 5: Print a formatted message showing all three
```



```python
# Step 1: Ask for the user's name
name = input("Enter your name: ")

# Step 2: Make it in UPPERCASE (for shouting style)
shouty = name.upper()

# Step 3: Make it in lowercase (for username style)

# Step 4: Create gamer tag: username + _player

# Step 5: Print a formatted message showing all three
```


```python
# Step 1: Ask for the user's name
name = input("Enter your name: ")

# Step 2: Make it in UPPERCASE (for shouting style)
shouty = name.upper()

# Step 3: Make it in lowercase (for username style)
username = name.lower()

# Step 4: Create gamer tag: username + _player

# Step 5: Print a formatted message showing all three
```


```python
# Step 1: Ask for the user's name
name = input("Enter your name: ")

# Step 2: Make it in UPPERCASE (for shouting style)
shouty = name.upper()

# Step 3: Make it in lowercase (for username style)
username = name.lower()

# Step 4: Create gamer tag: username + _player
tag = username + '_player'

# Step 5: Print a formatted message showing all three
```


```python
# Step 1: Ask for the user's name
name = input("Enter your name: ")

# Step 2: Make it in UPPERCASE (for shouting style)
shouty = name.upper()

# Step 3: Make it in lowercase (for username style)
username = name.lower()

# Step 4: Create gamer tag: username + _player
tag = username + '_player'

# Step 5: Print a formatted message showing all three
print()
print(f"SHOUTING STYLE: {shouty}")
print(f"username style: {username}")
print(f"Your gaming tag could be: {tag}")
```

```python
name = input("Enter your name: ")

shouty = name.upper()
username = name.lower()
tag = username + '_player'

print()
print(f"SHOUTING STYLE: {shouty}")
print(f"username style: {username}")
print(f"Your gaming tag could be: {tag}")
```

````
