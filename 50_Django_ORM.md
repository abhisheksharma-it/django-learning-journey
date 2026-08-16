# Django ORM

## What is ORM?

ORM ka full form hai:

Object Relational Mapping

ORM Python code ki help se database ke saath kaam karne deta hai.

---

## Without ORM

Hume directly SQL likhna pad sakta hai.

```sql
SELECT * FROM student;
```

---

## With Django ORM

```python
Student.objects.all()
```

---

## Why We Use ORM?

- SQL manually likhne ki zarurat kam hoti hai.
- Python se database handle kar sakte hain.
- Database operations easy ho jate hain.

---

## Example

```python
Student.objects.filter(age=20)
```

---

## Flow

Python Code

↓

Django ORM

↓

SQL Query

↓

Database

---

## Meri Language

ORM Python aur Database ke beech bridge ki tarah kaam karta hai.

Hum Python code likhte hain aur Django usko database query me convert karta hai.

---

## One Line Revision

Django ORM Python code se database ko handle karne deta hai.
