---
layout: quote
---

# Exercise: swap 2 variables

Asks for 2 values value1 and value2 then switches them.



<div v-click>
  <iframe
    v-if="$clicks >= 1"
    src="https://trinket.strivemath.org/embed/python3/38ab14ddd5b0?outputOnly=true&runOption=run&start=result"
    class="w-full h-80 rounded-lg border border-gray-500/40 mt-6"
  ></iframe>
</div>


---
layout: quote
---



# Instructions

<v-clicks>

1. This program takes two inputs. 
2. The first input is stored in a variable called `value1`. 
3. The second input is stored in a variable called `value2`.
4. Write a program that switches the values stored in the variables `value1` and `value2`.

</v-clicks>


---
layout: quote
---


    
# Starting code

```python {*|1-3|5-9|*} {lines:true}
value1 = input("First Value: ")
value2 = input("Second Value: ")
# Don't change the code above 

# Don't change the code below 
print()
print("Values after swap")
print(f"First Value:  {value1}")
print(f"Second Value: {value2}")
```


---
layout: quote
---
    
# Wrong Solution

````md magic-move {lines:true}
    
```python {*|1-2}
value1 = input("First Value: ")
value2 = input("Second Value: ")

value1 = value2
value2 = value1

print()
print("Values after swap")
print(f"First Value:  {value1}")
print(f"Second Value: {value2}")
```


```python {1-2|4-5|4|2,4}
value1 = '10'
value2 = '20'

value1 = value2
value2 = value1

print()
print("Values after swap")
print(f"First Value:  {value1}")
print(f"Second Value: {value2}")
```

```python {2,4|4-5|5|4}
value1 = '10'
value2 = '20'

value1 = '20'
value2 = value1

print()
print("Values after swap")
print(f"First Value:  {value1}")
print(f"Second Value: {value2}")
```

```python {5}
value1 = '10'
value2 = '20'

value1 = '20'
value2 = '20'

print()
print("Values after swap")
print(f"First Value:  {value1}")
print(f"Second Value: {value2}")
```


```python {7-10}
value1 = '10'
value2 = '20'

value1 = '20'
value2 = '20'

print()
print("Values after swap")
print(f"First Value:  {value1}")
print(f"Second Value: {value2}")
```

```python {7-10}
value1 = '10'
value2 = '20'

value1 = '20'
value2 = '20'

print()
print("Values after swap")
print(f"First Value:  20")
print(f"Second Value: 20")
```
````

---
layout: quote
---
    
# Correct Solution
    

````md magic-move {lines:true}

```python {*|1-2}
value1 = input("First Value: ")
value2 = input("Second Value: ")

# Create a third variable to help switch the values
save = value1
value1 = value2
value2 = save

print()
print("Values after swap")
print(f"First Value:  {value1}")
print(f"Second Value: {value2}")
```


```python {1-2|4-7}
value1 = '10'
value2 = '20'

# Create a third variable to help switch the values
save = value1
value1 = value2
value2 = save

print()
print("Values after swap")
print(f"First Value:  {value1}")
print(f"Second Value: {value2}")
```

```python {1,4-7}
value1 = '10'
value2 = '20'

# Create a third variable to help switch the values
save = '10'
value1 = value2
value2 = save

print()
print("Values after swap")
print(f"First Value:  {value1}")
print(f"Second Value: {value2}")
```

```python {2,4-7}
value1 = '10'
value2 = '20'

# Create a third variable to help switch the values
save = '10'
value1 = '20'
value2 = save

print()
print("Values after swap")
print(f"First Value:  {value1}")
print(f"Second Value: {value2}")
```

```python {5,7|4-7|9-12}
value1 = '10'
value2 = '20'

# Create a third variable to help switch the values
save = '10'
value1 = '20'
value2 = '10'

print()
print("Values after swap")
print(f"First Value:  {value1}")
print(f"Second Value: {value2}")
```

```python {9-12|*}
value1 = '10'
value2 = '20'

# Create a third variable to help switch the values
save = '10'
value1 = '20'
value2 = '10'

print()
print("Values after swap")
print(f"First Value:  20")
print(f"Second Value: 10")
```


```python
value1 = input("First Value: ")
value2 = input("Second Value: ")

# Create a third variable to help switch the values
save = value1
value1 = value2
value2 = save

print()
print("Values after swap")
print(f"First Value:  {value1}")
print(f"Second Value: {value2}")
```

````    
