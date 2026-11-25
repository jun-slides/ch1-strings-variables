---
layout: quote
---

# Variable Naming Rules

<v-clicks>

1. **No spaces,** use underscores instead
    - `user_name` (correct)
    - `user name` (error)
2. **Can't start with a number**
    - `name1` (correct)
    - `1name` (error)
3. **Only letters, numbers, and underscores**
    - `my_var_2` (correct)
    - `my-var` (error - hyphens not allowed)
4. **keywords not allowed**
    Keywords are words with special meaning, cannot be used to create variables
    - `if`, `else` `for`, `while` (error)

</v-clicks>

---
layout: quote
---


# Best Practices

<v-clicks>

- Use **descriptive names**: `user_name` not `n`
- Use **lowercase** with underscores (snake_case)
- Make names **meaningful**: `age` not `a`


```python  {*|1-4|6-9|*} {lines:true}
# Good variable names
user_name = "Angela"
user_age = 28
favorite_color = "blue"

# Bad variable names (but technically work)
x = "Angela"
a = 28
fc = "blue"
```


[QUESTION] Why is `user_name` better than `x`? Think about reading your code 6 months later!

</v-clicks>


---
layout: quote
---

# Exercise Identify valid variable names

Identify valid and invalid variable names. valid names are those that can be used as variables


```text
name
1st_place
age
full-name
_score
total$amount
user123
True
email_address
class
price_in_dollars
@home
lastName
def
Address_2
first name
is_valid
none
#temp
weight_kg
```

---
layout: quote
---

# Solution

```text
name          ✅
1st_place
age           ✅
full-name
_score        ✅
total$amount
user123       ✅
True
email_address ✅
class
price_in_dollars ✅
@home
lastName         ✅
def
Address_2        ✅
first name
is_valid         ✅
none             ✅
#temp 
weight_kg        ✅
```