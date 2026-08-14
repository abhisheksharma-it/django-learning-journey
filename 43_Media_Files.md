# Media Files in Django

## What are Media Files?

Media Files wo files hoti hain jo user upload karta hai.

Example

- Profile Photo
- Resume
- PDF
- Videos

---

## Difference

Static Files

↓

Developer ki files

Media Files

↓

User ki uploaded files

---

## Settings

```python
MEDIA_URL = "/media/"
```

```python
MEDIA_ROOT
```

---

## Flow

User

↓

Upload

↓

Media Folder

↓

Browser

---

## Meri Language

Media Files user ki uploaded files hoti hain.

Ye Static Files se alag hoti hain.

---

## One Line Revision

Media Files user ki uploaded files ko store karti hain.
