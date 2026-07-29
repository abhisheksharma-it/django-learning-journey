# urls.py

## What is urls.py?

urls.py Django ka URL Router hota hai.

Ye decide karta hai ki user kis URL par jayega to kaunsa View chalega.

Simple language me bole to urls.py URL ko View se connect karta hai.

---

## Why We Use urls.py?

Har website me bahut saare pages hote hain.

Example

- Home
- About
- Contact
- Login
- Register

In sab pages ka alag URL hota hai.

Ye mapping urls.py me hoti hai.

---

## Example

```python
from django.urls import path
from . import views

urlpatterns = [
    path('', views.home),
    path('about/', views.about),
]
```

---

## Flow

User Browser

↓

URL

↓

urls.py

↓

View

↓

Response

↓

Browser

---

## path() Function

path() URL ko kisi View se connect karta hai.

Syntax

```python
path("url/", views.function_name)
```

Example

```python
path("about/", views.about)
```

Jab user /about open karega tab about() View chalega.

---

## Meri Language

urls.py traffic police ki tarah kaam karta hai.

Ye user ko sahi View tak pahunchata hai.

---

## Interview Definition

urls.py is responsible for mapping URLs to Views.
