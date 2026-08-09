# URL Template Tags

## What are URL Template Tags?

URL Template Tag Django ka special tag hai.

Ye HTML ke andar URL generate karne ke liye use hota hai.

Hardcode URL likhne ki zarurat nahi padti.

---

## Why We Use URL Template Tags?

- Hardcoded URL se bachne ke liye.
- Agar URL change ho jaye to HTML change nahi karna padta.
- Code reusable aur maintainable hota hai.

---

## Syntax

```html
{% url 'home' %}
```

---

## Example

### urls.py

```python
urlpatterns = [
    path('', views.home, name='home'),
]
```

### home.html

```html
<a href="{% url 'home' %}">Home</a>
```

---

## Flow

HTML

↓

URL Template Tag

↓

urls.py

↓

Correct URL

↓

Browser

---

## Meri Language

HTML ke andar direct URL likhne ki jagah

```
/home/
```

hum

```html
{% url 'home' %}
```

likhte hain.

Agar future me URL change ho jaye to HTML file ko change nahi karna padta.

---

## One Line Revision

URL Template Tag HTML me Dynamic URL banane ke liye use hota hai.
