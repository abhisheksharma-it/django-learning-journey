# get() Method in Django

## What is get()?

get() database se sirf ek record return karta hai.

Condition unique honi chahiye.

---

## Syntax

```python
Model.objects.get(id=1)
```

---

## Example

```python
Student.objects.get(id=1)
```

Output

Ek Student Object

---

## Difference

filter()

↓

Multiple Records

get()

↓

Single Record

---

## Note

Agar record na mile

↓

Error

Agar ek se jyada record mile

↓

Error

---

## Meri Language

Jab sirf ek hi record lana ho tab get() use karte hain.

---

## One Line Revision

get() ek single object return karta hai.
