# HTTP Request Methods (GET & POST)

## What is HTTP Request?

Jab browser aur server ke beech data transfer hota hai to HTTP Request use hoti hai.

Django me sabse common Request Methods

- GET
- POST

---

## GET Method

GET data ko server se lene ke liye use hota hai.

Example

- Search
- Open Page
- View Products

Data URL me dikhta hai.

Example

```
http://127.0.0.1:8000/search/?name=avii
```

---

## POST Method

POST data ko server ko bhejne ke liye use hota hai.

Example

- Login
- Registration
- Contact Form

POST me data URL me show nahi hota.

---

## Difference

GET

- Data Fetch karta hai.
- Data URL me dikhta hai.
- Secure nahi hota.

POST

- Data Server ko bhejta hai.
- Data URL me nahi dikhta.
- GET se jyada Secure hai.

---

## Flow

Browser

↓

GET / POST

↓

Django View

↓

Response

↓

Browser

---

## Meri Language

GET ka use data dekhne ke liye hota hai.

POST ka use data save ya submit karne ke liye hota hai.

---

## One Line Revision

GET = Data Read

POST = Data Submit
