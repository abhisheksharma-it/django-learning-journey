# Caching in Django

## What is Caching?

Caching frequently used data ko temporarily store karna hai.

Isse same data baar-baar database ya server se fetch nahi karna padta.

---

## Why We Use Cache?

- Website Fast Hoti Hai
- Database Load Kam Hota Hai
- Server Performance Improve Hoti Hai

---

## Simple Example

Without Cache

```text
User
 ↓
Database
 ↓
Response
```

With Cache

```text
User
 ↓
Cache
 ↓
Response
```

---

## Common Cache Backends

- Redis
- Memcached
- Database Cache
- Local Memory Cache

---

## Meri Language

Cache frequently used data ko temporarily store karta hai taaki website faster chale.

---

## One Line Revision

Caching performance improve karne ke liye frequently used data ko temporarily store karti hai.
