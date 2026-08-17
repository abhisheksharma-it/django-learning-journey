# models.py

## What is models.py?

models.py database ki table ka blueprint hota hai.

Hum database ka structure Python me models.py ke andar likhte hain.

Baad me Django uske according database me table bana deta hai.

---

## Why We Use Models?

Database me data store karne ke liye.

Example

Student Data

- Name
- Age
- Email

Ye sab Model me define kiya jata hai.

---

## Example

```python
from django.db import models

class Student(models.Model):

    name = models.CharField(max_length=100)

    age = models.IntegerField()
```

---

## After Creating Model

Command

```bash
python manage.py makemigrations
```

Migration file banegi.

Then

```bash
python manage.py migrate
```

Database me Student table create ho jayegi.

---

## Flow

Model

↓

makemigrations

↓

Migration File

↓

migrate

↓

Database Table

---

## Meri Language

Model database ki table ka design hota hai.

Hum pehle Python me design banate hain.

Phir migrate karke Django database me actual table bana deta hai.

---

## Interview Definition

A Model is a Python class that represents a database table.
