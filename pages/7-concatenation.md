---
layout: quote
---

# Strings Concatenation

<v-clicks>

Use the `+` operator to join strings together:

````md magic-move {lines:true}
```python
print("Hello" + "Angela")
```

```python
print("HelloAngela")
```

```text
HelloAngela
```

```python
print("Hello" + "Angela") # Outputs: HelloAngela
```

````


Notice there's no space! Python doesn't add spaces automatically.
<br>
<br>
<br>

### Adding space

````md magic-move {lines:true}
```python
print("Hello" + " " + "Angela")  
```

```python
print("Hello Angela")  
```

```text
Hello Angela
```

```python
print("Hello" + " " + "Angela")   # Outputs: Hello Angela
```
````

</v-clicks>


---
layout: quote
---

# Repeating a string using `*`

Use `*` operator if you want to repeat a string

<v-clicks>


````md magic-move {lines:true}
```python
print('abc' * 3)
```

```python
print('abcabcabc')
```

```text
abcabcabc
```

```python
print('abc' * 3)  # abcabcabc
```

````


[QUESTION] How would you add a space between abc to get ‘abc abc abc’ ?
</v-clicks>

---
layout: quote
---

# Concatenation exercises 1
    

```python
s1 = 'ant'
s2 = 'bat'
s3 = 'cod'

# Write Python expressions using s1, s2, and s3 that evaluate to:
# (a) 'ant bat cod'
# (b) 'ant ant ant ant ant ant ant ant ant ant '
# (c) 'ant bat bat cod cod cod'
# (d) 'ant bat ant bat ant bat ant bat ant bat ant bat ant bat '
# (e) 'batbatcod batbatcod batbatcod batbatcod batbatcod '
```

---
layout: quote
---

# Concatenation exercises 2
    


```python
s1 = '-' 
s2 = '+'

# Now write string expressions involving s1 and s2 that evaluate to:
# (a) '-+' 
# (b) '-+-' 
# (c) '+––'
# (d) '+––+––'
# (e) '+––+––+––+––+––+––+––+––+––+––+' 
# (f) '+–+++––+–+++––+–+++––+–+++––+–+++––'
# Try to make your string expressions as succinct as you can.
```
    
