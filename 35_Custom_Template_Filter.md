# Custom Template Filter in Django

## What is Custom Template Filter?

Jab Django ke default filters kaafi na ho,

tab hum apna khud ka filter bana sakte hain.

Isse Custom Template Filter kehte hain.

---

## Why We Use?

- Custom Logic
- Text Change
- Price Format
- Date Format

---

## Folder Structure

```
app/

templatetags/

custom_filter.py
```

---

## Example

```python
{{ name|upper }}
```

Apna Filter

```python
{{ name|myfilter }}
```

---

## Flow

Template

↓

Custom Filter

↓

Modified Output

↓

Browser

---

## Meri Language

Agar apni requirement ka filter chahiye ho,

to Custom Template Filter banate hain.

---

## One Line Revision

Custom Template Filter apni logic template me use karne ke liye hota hai.
