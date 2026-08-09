# Extends and Include

## What is Extends?

Extends ka use Parent Template ko inherit karne ke liye hota hai.

Ek hi layout ko baar-baar likhne ki zarurat nahi padti.

---

## Syntax

```html
{% extends "base.html" %}
```

---

## What is Include?

Include ka use kisi HTML file ko dusri HTML file ke andar add karne ke liye hota hai.

---

## Syntax

```html
{% include "header.html" %}
```

---

## Example

base.html

- Header
- Navbar
- Footer

home.html

```html
{% extends "base.html" %}
```

header.html

```html
{% include "header.html" %}
```

---

## Why We Use It?

- Code Repeat nahi hota.
- Website maintain karna easy hota hai.
- Time bach jata hai.

---

## Meri Language

Extends ka matlab Parent Template ko use karna.

Include ka matlab kisi HTML file ko dusri HTML file ke andar jodna.

Dono ka use code ko clean aur reusable banane ke liye hota hai.

---

## One Line Revision

Extends = Parent Template Inherit

Include = Dusri HTML File Add Karna
