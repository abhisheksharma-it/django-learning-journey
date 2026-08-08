# Migrations in Django

## What is Migration?

Migration Model aur Database ke beech bridge ka kaam karti hai.

Ye database me changes apply karti hai.

---

## Commands

Create Migration

```bash
python manage.py makemigrations
```

Apply Migration

```bash
python manage.py migrate
```

---

## Flow

Model

↓

makemigrations

↓

Migration File

↓

migrate

↓

Database Table

---

## Meri Language

Pehle hum Model banate hain.

makemigrations uska blueprint banata hai.

migrate database me actual table bana deta hai.

---

## One Line Revision

Migration Model ke changes ko Database me apply karti hai.
