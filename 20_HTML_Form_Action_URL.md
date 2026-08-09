# HTML Form Action URL

## What is Form Action?

Form Action batata hai ki Form submit hone ke baad request kis URL par jayegi.

Simple language me bole to

Form

↓

Action URL

↓

Django View

↓

Response

---

## Syntax

```html
<form action="URL" method="POST">

</form>
```

---

## Example

```html
<form action="/contact/" method="POST">

{% csrf_token %}

<input type="text" name="username">

<input type="submit" value="Submit">

</form>
```

---

## Using Django URL Template Tag

Hardcoded URL likhne ki jagah

```html
<form action="{% url 'contact' %}" method="POST">

{% csrf_token %}

</form>
```

Ye best practice hai.

---

## Why We Use Action?

Action batata hai

Form submit hone ke baad data kis page ya View me jayega.

---

## Flow

User

↓

Fill Form

↓

Submit Button

↓

Action URL

↓

View

↓

Response

---

## Meri Language

Action URL Form ka destination hota hai.

Jahan user ka data bhejna hota hai wahi Action me likhte hain.

Agar Django use kar rahe hain to

```html
{% url 'contact' %}
```

use karna best practice hai.

---

## One Line Revision

Action URL batata hai Form submit hone ke baad request kis URL ya View ke paas jayegi.
