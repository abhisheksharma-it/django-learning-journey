# Function Based Views (FBV)

## What is Function Based View?

Function Based View (FBV) ek normal Python function hota hai.

Ye user ki request receive karta hai aur response return karta hai.

---

## Example

```python
from django.http import HttpResponse

def home(request):
    return HttpResponse("Welcome")
```

---

## Why We Use FBV?

- Simple Code
- Easy to Understand
- Beginners Friendly

---

## Flow

User

↓

URL

↓

Function View

↓

Response

↓

Browser

---

## Advantages

- Easy to Learn
- Easy to Write
- Best for Small Projects

---

## Meri Language

FBV ek normal Python function hai.

Ye request leta hai aur browser ko response bhej deta hai.

---

## One Line Revision

Function Based View ek Python function hota hai jo request handle karta hai.
