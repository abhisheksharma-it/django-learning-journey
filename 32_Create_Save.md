# Create and Save Data in Django

## Why We Use?

Database me naya data insert karne ke liye.

---

## Step 1

Object banao.

```python
student = Student()
```

---

## Step 2

Value do.

```python
student.name = "Abhishek"
student.age = 22
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
student = Student()

student.name = "Abhishek"
student.age = 22

student.save()
```

---

## Flow

Browser

↓

View

↓

Model

↓

save()

↓

Database

---

## Meri Language

Pehle object banao.

Usme value bharo.

Phir save() se database me store kar do.

---

## One Line Revision

save() database me naya record insert karta hai.
