# Dynamic URL in Django

## What is Dynamic URL?

Dynamic URL me value change hoti rehti hai.

Example

```
product/1/
product/2/
product/3/
```

Yahan sirf ID change ho rahi hai.

---

## Syntax

```python
path("product/<int:id>/", views.product)
```

---

## Example

```python
def product(request, id):
    return HttpResponse(id)
```

---

## Meri Language

Dynamic URL ka matlab URL ke andar variable pass karna.

Ek hi View alag-alag data dikha sakta hai.

---

## One Line Revision

Dynamic URL URL ke through variable bhejne ke liye use hota hai.
