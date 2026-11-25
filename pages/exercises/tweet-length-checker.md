---
layout: quote
---

# Example 2: Tweet Length Checker


 Checks if a message fits in a tweet (280 characters) using len().

<div v-click>
  <iframe
    v-if="$clicks >= 1"
    src="https://trinket.strivemath.org/embed/python3/84109da44c36?outputOnly=true&runOption=run&start=result"
    class="w-full h-80 rounded-lg border border-gray-500/40 mt-6"
  ></iframe>
</div>

---
layout: quote
---

# Instructions

<v-clicks>

1. Ask user to type their tweet
2. Count the characters using len()
3. Show how many characters they used
4. Show how many characters they have left (max limit is 280)


</v-clicks>

---
layout: quote
---

# Starting code

```python  {lines: true}
# Step 1: Ask user to type their tweet

# Step 2: Count the characters using len()

# Step 3: Show how many characters they used

# Step 4: Show how many characters they have left (limit is 280)
```

---
layout: quote
---

# Solution


<v-clicks>

````md magic-move {lines:true}
```python
# Step 1: Ask user to type their tweet

# Step 2: Count the characters using len()

# Step 3: Show how many characters they used

# Step 4: Show how many characters they have left (limit is 280)
```


```python
# Step 1: Ask user to type their tweet
tweet = input("Write your tweet: ")

# Step 2: Count the characters using len()

# Step 3: Show how many characters they used

# Step 4: Show how many characters they have left (limit is 280)
```


```python
# Step 1: Ask user to type their tweet
tweet = input("Write your tweet: ")

# Step 2: Count the characters using len()
length = len(tweet)

# Step 3: Show how many characters they used

# Step 4: Show how many characters they have left (limit is 280)
```

```python
# Step 1: Ask user to type their tweet
tweet = input("Write your tweet: ")

# Step 2: Count the characters using len()
length = len(tweet)

# Step 3: Show how many characters they used
print(f"Characters used: {length}")

# Step 4: Show how many characters they have left (limit is 280)
```

```python
# Step 1: Ask user to type their tweet
tweet = input("Write your tweet: ")

# Step 2: Count the characters using len()
length = len(tweet)

# Step 3: Show how many characters they used
print(f"Characters used: {length}")

# Step 4: Show how many characters they have left (limit is 280)
remaining = 280 - length
print(f"Characters remaining: {remaining}")
```


```python
tweet = input("Write your tweet: ")

length = len(tweet)
remaining = 280 - length

print(f"Characters used: {length}")
print(f"Characters remaining: {remaining}")
```

```python
tweet = input("Write your tweet: ")

length = len(tweet)
remaining = 280 - length

print()
print(f"Your tweet: {tweet}")
print(f"Characters used: {length}")
print(f"Characters remaining: {remaining}")
```
````


[MODIFY] Add a warning message if they go over 280 characters (we'll learn proper if-statements next lesson, but try it!).
</v-clicks>