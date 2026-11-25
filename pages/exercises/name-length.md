---
layout: quote
---

# Exercise: Find Name Length

<div v-click>
  <iframe
    v-if="$clicks >= 1"
    src="https://trinket.strivemath.org/embed/python3/f91585056c15?outputOnly=true&start=result&runOption=run"
    class="w-full h-80 rounded-lg border border-gray-500/40 mt-6"
  ></iframe>
</div>

---
layout: quote
---

# Solution

````md magic-move {lines:true}
```python {*|1}
name = input("Enter your name: ")
length = len(name)

print()
print(f"{name} contains {length} letters.")
```

```python {1|2}
name = "Muhammad"
length = len(name)

print()
print(f"{name} contains {length} letters.")
```

```python {2}
name = "Muhammad"
length = len("Muhammad")

print()
print(f"{name} contains {length} letters.")
```


```python {2}
name = "Muhammad"
length = 8

print()
print(f"{name} contains {length} letters.")
```


```python {4|5}
name = "Muhammad"
length = 8

print()
print(f"{name} contains {length} letters.")
```

```python {5|*}
name = "Muhammad"
length = 8

print()
print("Muhammad contains 8 letters.")
```

```python 
name = input("Enter your name: ")
length = len(name)

print()
print(f"{name} contains {length} letters.")
```

````
