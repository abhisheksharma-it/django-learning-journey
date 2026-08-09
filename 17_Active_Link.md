# Highlight Active Link in Django

## What is Active Link?

Active Link ka matlab jis page par user abhi hai us link ko highlight karna.

Example

Home | About | Contact

Agar user Home page par hai to Home ka color alag dikhega.

---

## Why We Use Active Link?

- User ko current page pata chal jata hai.
- Website Professional lagti hai.
- Navigation easy ho jati hai.

---

## Example

```html
<li class="{% if request.path == '/' %}active{% endif %}">
    <a href="{% url 'home' %}">Home</a>
</li>
```

---

## CSS

```css
.active{
    color:red;
    font-weight:bold;
}
```

---

## Flow

Current URL

↓

Compare URL

↓

Active Class

↓

Highlighted Link

---

## Meri Language

User jis page par hota hai us page ke link ka color ya design change kar dete hain.

Isse user ko pata chal jata hai ki wo abhi kis page par hai.

---

## One Line Revision

Active Link current page ke navigation link ko highlight karta hai.
