---
layout: quote
section: Variables
---

#  Variables
Now let's store information:

<v-clicks>

```python
name = "Sarah"
print(name)

```
</v-clicks>

<v-clicks>

- `name` is a **variable** - a container that holds information
- `"Sarah"` is a **string** - text wrapped in quotes
- `=` means "store this value"
</v-clicks>


---
layout: two-cols
layoutClass: gap-16
---

# Python reads top to bottom

```py {1|2|3|4}
name = "Jack"
print(name)
name = "Angela"
print(name)
```

::right::


<div class="mt-6">

**`name` holds:**

<div class="mt-3 p-4 rounded-lg border border-gray-500/40 text-2xl">
  <span v-if="$clicks < 2">📦 "Jack"</span>
  <span v-else>📦 "Angela"</span>
</div>

</div>

<div class="mt-8">

**Console:**

<div class="mt-3 p-4 rounded-lg bg-black/40 font-mono space-y-1 min-h-24">
  <div v-click="1">Jack</div>
  <div v-click="3">Angela</div>
</div>

</div>

