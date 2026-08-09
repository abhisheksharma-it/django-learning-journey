# Superuser in Django

## What is Superuser?

Superuser Django ka Admin Account hota hai.

Iske paas project ki saari permissions hoti hain.

Superuser website ke data ko manage kar sakta hai.

---

## Why We Use Superuser?

- Django Admin Panel me login karne ke liye.
- Data Add karne ke liye.
- Data Update karne ke liye.
- Data Delete karne ke liye.
- Users ko manage karne ke liye.

---

## Command

Create Superuser

```bash
python manage.py createsuperuser
```

---

## It Will Ask

```
Username:
```

```
Email:
```

```
Password:
```

Password set karne ke baad Superuser create ho jata hai.

---

## Login URL

```
http://127.0.0.1:8000/admin/
```

Yahan Username aur Password se login karte hain.

---

## Meri Language

Superuser website ka Owner ya Admin Account hota hai.

Sirf jiske paas Username aur Password hoga wahi Django Admin Panel me login karke website ka data manage kar sakta hai.

Normal users Superuser nahi hote.

---

## One Line Revision

Superuser Django ka Admin Account hota hai jiske paas sabhi permissions hoti hain.
