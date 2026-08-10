# Models in Django

## What is Model?

Model database ki table ka Python representation hota hai.

---

## Example

```python
from django.db import models

class Student(models.Model):
    name = models.CharField(max_length=100)
    age = models.IntegerField()
```

---

## Why We Use Models?

- Database Table Banana
- Data Save Karna
- Data Read Karna
- Data Update Karna

---

## Flow

Model

↓

Migration

↓

Database Table

---

## Meri Language

Model database ka design hota hai.

Jo field Model me likhte hain wahi table me ban jati hain.

---

## One Line Revision

Model Python me database table ko represent karta hai.
