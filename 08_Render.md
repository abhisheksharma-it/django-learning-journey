# Render in Django

## What is Render?

render() HTML page ko browser me dikhane ke liye use hota hai.

Simple language me bole to

Python + HTML

↓

Browser

---

## Syntax

```python
render(request, "home.html")
```

---

## Example

```python
from django.shortcuts import render

def home(request):
    return render(request, "home.html")
```

---

## Meri Language

render() HTML file ko browser me bhejne ka kaam karta hai.

Agar website ka page dikhana hai to render() use karte hain.

---

## One Line Revision

render() HTML template ko browser me display karta hai.
