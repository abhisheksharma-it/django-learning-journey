# views.py

## What is views.py?

View ek Python function ya class hota hai.

Ye user ki request receive karta hai aur browser ko response return karta hai.

---

## Why We Use Views?

User jab website open karta hai to request Django ke paas aati hai.

Us request ko handle karne ka kaam View karta hai.

---

## Example

```python
from django.http import HttpResponse

def home(request):
    return HttpResponse("Welcome")
```

---

## Flow

User

↓

Request

↓

View

↓

Response

↓

Browser

---

## request

request user ki information lekar aata hai.

Jaise

- URL
- Form Data
- Login Information

---

## return

return browser ko response bhejta hai.

Example

```python
return HttpResponse("Hello")
```

Browser me Hello show hoga.

---

## Meri Language

View waiter ki tarah hota hai.

User order deta hai.

View response lekar browser ko de deta hai.

---

## Interview Definition

A View receives the request, processes it and returns a response.
