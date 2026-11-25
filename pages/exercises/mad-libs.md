---
layout: quote
---

# Example 1: Mad Libs Game


Asks the user for random words, then puts them into a funny story template.

<div v-click>
  <iframe
    v-if="$clicks >= 1"
    src="https://trinket.strivemath.org/embed/python3/5214be8341f7?outputOnly=true&start=result&runOption=run"
    class="w-full h-80 rounded-lg border border-gray-500/40 mt-6"
  ></iframe>
</div>


---
layout: quote
---

# Instructions

<v-clicks>

1. Ask user for an animal
2. Ask user for a food
3. Ask user for a place
4. Print the silly story using an f-string

</v-clicks>

---
layout: quote
---

# Starting code

```python  {lines: true}
# Step 1: Ask user for an animal

# Step 2: Ask user for a food

# Step 3: Ask user for a place

# Step 4: Print the silly story using f-string
```

---
layout: quote
---

# Solution


<v-clicks>

````md magic-move {lines:true}
```python 
# Step 1: Ask user for an animal

# Step 2: Ask user for a food

# Step 3: Ask user for a place

# Step 4: Print the silly story using f-string
```

```python 
# Step 1: Ask user for an animal
animal = input("Enter an animal: ")

# Step 2: Ask user for a food
food = input("Enter a food: ")

# Step 3: Ask user for a place
place = input("Enter a place: ")

# Step 4: Print the silly story using f-string
```

```python 
# Step 1: Ask user for an animal
animal = input("Enter an animal: ")

# Step 2: Ask user for a food
food = input("Enter a food: ")

# Step 3: Ask user for a place
place = input("Enter a place: ")

# Step 4: Print the silly story using f-string
print(f"Yesterday I saw a {animal} eating {food} at the {place}.")
```
````


**\[MODIFY\]** Add one more input (maybe an action ending in -ing?) and update the story.
</v-clicks>