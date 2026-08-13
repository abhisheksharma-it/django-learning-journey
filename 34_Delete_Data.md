# Delete Data in Django

## What is Delete?

Database se record ko permanently remove karna Delete kehlata hai.

---

## Step 1

Record ko get karo.

```python
student = Student.objects.get(id=1)
```

---

## Step 2

Delete karo.

```python
student.delete()
```

---

## Complete Example

```python
student = Student.objects.get(id=1)

student.delete()
```

---

## Flow

Database

↓

get()

↓

delete()

↓

Record Removed

---

## Meri Language

Record ko pehle nikalo.

Phir delete() likho.

Record database se remove ho jayega.

---

## One Line Revision

delete() record ko permanently remove karta hai.
