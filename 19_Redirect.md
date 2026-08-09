# Redirect in Django

## What is Redirect?

Redirect ka matlab ek page se automatically dusre page par bhejna.

---

## Why We Use Redirect?

- Login ke baad Home Page
- Logout ke baad Login Page
- Form Submit hone ke baad Success Page

---

## Syntax

```python
from django.shortcuts import redirect
```

---

## Example

```python
from django.shortcuts import redirect

def home(request):

    return redirect("about")
```

---

## Flow

User

↓

Home

↓

Redirect

↓

About

---

## Meri Language

Redirect ka matlab user ko bina manually click kiye dusre page par bhejna.

---

## One Line Revision

Redirect user ko ek page se dusre page par bhejta hai.
