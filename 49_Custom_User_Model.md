# Custom User Model in Django

## What is Custom User Model?

Django ka default User Model hota hai.

Lekin agar hume apne according User ke fields add/change karne hain,
to Custom User Model bana sakte hain.

---

## Why We Use It?

Example:

- Phone Number
- Profile Picture
- Date of Birth
- Extra User Information

---

## Simple Idea

Default User

↓

Custom User

↓

Apne Fields Add

---

## Example

```python
from django.contrib.auth.models import AbstractUser

class User(AbstractUser):
    phone = models.CharField(max_length=15)
```

---

## Meri Language

Django ke default User me apni requirement ke according extra fields add karne ke liye Custom User Model use karte hain.

---

## One Line Revision

Custom User Model = Django User Model ko apni requirement ke according customize karna.
