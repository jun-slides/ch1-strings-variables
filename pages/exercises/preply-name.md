---
layout: quote
---

# Example 4: Preply name generator

Takes a first and last name and formats them into a Preply-style display name (titlecase first name + uppercase first letter of last name + period).

<div v-click>
  <iframe
    v-if="$clicks >= 1"
    src="https://trinket.strivemath.org/embed/python3/ceda3ac1a21e?outputOnly=true&runOption=run&start=result"
    class="w-full h-80 rounded-lg border border-gray-500/40 mt-6"
  ></iframe>
</div>


---
layout: quote
---
    
    
# Instructions

<v-clicks>

1. Ask for the first name
2. Ask for the last name
3. Create the preply name: `first name title` + `last name first letter upper case` + `.`
4. Print a formatted message showing the preply name

</v-clicks>


---
layout: quote
---
    

# Starting code
    
```python {lines:true}
# Step 1: Ask for first name

# Step 2: Ask for second name

# Step 3: Create preply name
# preply name = first name in titlecase + second name first letter in uppercase + .
    
# Step 4: Print the preply name
```

---
layout: quote
---
    
   
# Solution

    
````md magic-move {lines:true}    
```python {*|1-3}
# take input
firstname = input('First name: ')
lastname = input('Last name: ')

# create preply name
preply_name = firstname.title() + ' ' + lastname[0].title() + '.'

# display preply name
print(f"Your preply name is: '{preply_name}'")
```

```python {1-3|5-6}
# take input
firstname = 'muhammad'
lastname = 'junaid'

# create preply name
preply_name = firstname.title() + ' ' + lastname[0].title() + '.'

# display preply name
print(f"Your preply name is: '{preply_name}'")
```

```python {5-6}
# take input
firstname = 'muhammad'
lastname = 'junaid'

# create preply name
preply_name = 'muhammad'.title() + ' ' + lastname[0].title() + '.'

# display preply name
print(f"Your preply name is: '{preply_name}'")
```

```python {5-6}
# take input
firstname = 'muhammad'
lastname = 'junaid'

# create preply name
preply_name = 'Muhammad' + ' ' + lastname[0].title() + '.'

# display preply name
print(f"Your preply name is: '{preply_name}'")
```

```python {5-6}
# take input
firstname = 'muhammad'
lastname = 'junaid'

# create preply name
preply_name = 'Muhammad' + ' ' + 'j'.title() + '.'

# display preply name
print(f"Your preply name is: '{preply_name}'")
```


```python {5-6}
# take input
firstname = 'muhammad'
lastname = 'junaid'

# create preply name
preply_name = 'Muhammad' + ' ' + 'J' + '.'

# display preply name
print(f"Your preply name is: '{preply_name}'")
```

```python {5-6|8-9}
# take input
firstname = 'muhammad'
lastname = 'junaid'

# create preply name
preply_name = 'Muhammad J.'

# display preply name
print(f"Your preply name is: '{preply_name}'")
```

```python {8-9|*}
# take input
firstname = 'muhammad'
lastname = 'junaid'

# create preply name
preply_name = 'Muhammad J.'

# display preply name
print(f"Your preply name is: 'Muhammad J.'")
```
````
    

