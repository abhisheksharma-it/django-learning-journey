# Messages Framework in Django

## What is Messages Framework?

Messages Framework user ko notification dikhane ke liye use hota hai.

Example

- Login Successful
- Registration Completed
- Data Saved
- Error Message

---

## Why We Use?

- Success Message
- Error Message
- Warning Message
- Information Message

---

## Example

```python
from django.contrib import messages

messages.success(request, "Data Saved Successfully")
```

---

## Types of Messages

```python
messages.success()
```

```python
messages.error()
```

```python
messages.warning()
```

```python
messages.info()
```

---

## Flow

User

↓

Action

↓

Message

↓

Browser

---

## Meri Language

Messages Framework user ko batata hai ki operation successful hua ya error aaya.

---

## One Line Revision

Messages Framework user ko notification dikhata hai.
