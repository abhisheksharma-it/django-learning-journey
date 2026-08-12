# first() and last() in Django

## What is first()?

Table ka pehla record return karta hai.

```python
Student.objects.first()
```

---

## What is last()?

Table ka last record return karta hai.

```python
Student.objects.last()
```

---

## Why We Use?

- Latest Record
- Oldest Record
- First User
- Last User

---

## Flow

Database

↓

first()

↓

First Record

Database

↓

last()

↓

Last Record

---

## Meri Language

Pehla record chahiye to first()

Last record chahiye to last()

---

## One Line Revision

first() pehla aur last() aakhri record return karta hai.
