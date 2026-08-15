# Class Based Views (CBV)

## What is Class Based View?

Class Based View ek Python Class hoti hai.

Ye Function Based View ka advanced version hai.

---

## Example

```python
from django.views import View

class Home(View):

    def get(self, request):
        pass
```

---

## Why We Use CBV?

- Less Code
- Reusable
- Better Structure

---

## Flow

User

↓

URL

↓

Class View

↓

Response

↓

Browser

---

## Difference

FBV

↓

Function

CBV

↓

Class

---

## Meri Language

CBV Function ki jagah Class use karti hai.

Bade projects me mostly CBV use hoti hai.

---

## One Line Revision

Class Based View request handle karne ke liye Python Class use karti hai.
