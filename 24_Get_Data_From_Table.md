# Get Data From Table

## What is Get Data?

Database me save data ko retrieve karna.

---

## Example

```python
Student.objects.all()
```

Ye table ka sara data laata hai.

---

## Other Examples

```python
Student.objects.get(id=1)
```

```python
Student.objects.filter(age=20)
```

---

## Flow

Database

↓

ORM

↓

View

↓

Browser

---

## Meri Language

Database me jo data save hai use Django ORM ki help se nikalte hain.

---

## One Line Revision

ORM ki help se database ka data retrieve karte hain.
