# Filter in Django

## What is filter()?

filter() database se condition ke hisab se data nikalta hai.

Ye sirf matching records return karta hai.

---

## Syntax

```python
Model.objects.filter(condition)
```

---

## Example

```python
Student.objects.filter(name="Abhishek")
```

Output

Sirf Abhishek naam wale students.

---

## Multiple Conditions

```python
Student.objects.filter(age=20)
```

```python
Student.objects.filter(city="Delhi")
```

---

## Why We Use?

- Search Data
- Login Data
- Category Wise Data
- User Wise Data

---

## Flow

Database

↓

filter()

↓

Matching Records

↓

Browser

---

## Meri Language

Jab hume sirf specific data chahiye hota hai tab filter() use karte hain.

---

## One Line Revision

filter() condition ke according data return karta hai.
