# Django Forms

## What is Django Form?

Django Form user se data lene aur validate karne ke liye use hota hai.

HTML Form se better aur secure hota hai.

---

## Why We Use Django Forms?

- Validation
- Clean Code
- Error Handling
- Security

---

## Example

```python
from django import forms

class ContactForm(forms.Form):
    name = forms.CharField()
    email = forms.EmailField()
```

---

## Flow

User

↓

Form

↓

Validation

↓

View

↓

Response

---

## Meri Language

Django Form user ka data lene aur automatically check karne ke liye use hota hai.

---

## One Line Revision

Django Forms user input ko validate aur process karte hain.
