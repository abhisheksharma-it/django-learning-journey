# Limiting Query Results

## What is Limiting Query?

Kabhi-kabhi hume sara data nahi chahiye hota.

Sirf kuch records chahiye hote hain.

---

## Example

First 5 Records

```python
Student.objects.all()[:5]
```

First Record

```python
Student.objects.first()
```

Last Record

```python
Student.objects.last()
```

---

## Why We Use?

- Fast Loading
- Less Data
- Pagination

---

## Flow

Database

↓

Limit

↓

Required Records

↓

Browser

---

## Meri Language

Limiting ka matlab sirf utna hi data lana jitni zarurat ho.

---

## One Line Revision

Limiting Query sirf required records return karti hai.
