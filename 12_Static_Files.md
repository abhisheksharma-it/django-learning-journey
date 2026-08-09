# Static Files (CSS, JavaScript & Images)

## What are Static Files?

Static Files wo files hoti hain jo website ka Design aur Look banati hain.

Ye files change nahi hoti jab user request bhejta hai.

---

## Static Files Types

- CSS
- JavaScript
- Images

---

## CSS

CSS website ko Design aur Styling dene ke liye use hoti hai.

Example

- Colors
- Fonts
- Buttons
- Layout

---

## JavaScript

JavaScript website me functionality add karti hai.

Example

- Button Click
- Popup
- Validation
- Slider

---

## Images

Images website ko attractive banati hain.

Example

- Logo
- Banner
- Product Image
- Profile Photo

---

## Folder Structure

project/

static/

│

├── css/

│      style.css

│

├── js/

│      script.js

│

└── images/

       logo.png

---

## HTML Example

```html
{% load static %}

<link rel="stylesheet" href="{% static 'css/style.css' %}">

<script src="{% static 'js/script.js' %}"></script>

<img src="{% static 'images/logo.png' %}" alt="Logo">
```

---

## Flow

Browser

↓

HTML

↓

Static Files

↓

CSS + JavaScript + Images

↓

Website

---

## Meri Language

Static Files website ka Design aur Functionality banati hain.

CSS Design karti hai.

JavaScript website ko interactive banati hai.

Images website ko attractive banati hain.

---

## One Line Revision

Static Files = CSS + JavaScript + Images
Ye website ka Design aur Functionality banati hain.
