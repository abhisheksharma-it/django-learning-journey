# Update Data in Django

## What is Update?

Database me pehle se existing data ko change karna Update kehlata hai.

---

## Step 1

Record ko get karo.

```python
student = Student.objects.get(id=1)
```

---

## Step 2

Value change karo.

```python
student.name = "Rahul"
```

---

## Step 3

Save karo.

```python
student.save()
```

---

## Complete Example

```python
student = Student.objects.get(id=1)

student.name = "Rahul"

student.save()
```

---

## Flow

Database

↓

get()

↓

Update Value

↓

save()

↓

Database

---

## Meri Language

Pehle record nikalo.

Uski value change karo.

Phir save() kar do.

---

## One Line Revision

save() existing object ko bhi update karta hai.
