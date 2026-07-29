# settings.py

## What is settings.py?

settings.py Django project ki main configuration file hoti hai.

Is file me project ki saari important settings hoti hain.

Simple language me bole to ye project ka **Control Panel** hai.

Yahin se decide hota hai ki project kaise kaam karega.

---

## settings.py Ka Kya Kaam Hai?

- Database configure karna
- Installed Apps ko register karna
- Templates ki setting
- Static Files (CSS, JS, Images)
- Media Files
- Time Zone
- Language
- Security Settings
- Debug Mode
- Secret Key

---

## Important Settings

### 1. INSTALLED_APPS

Yahan un sabhi apps ke naam hote hain jo project me use honge.

Example:

```python
INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'blog',
]
```

Agar hum naya app banate hain to usko yahan register karna padta hai.

---

### 2. DATABASES

Ye batata hai project kis database ko use karega.

Default database SQLite hoti hai.

Example:

```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.sqlite3',
        'NAME': BASE_DIR / 'db.sqlite3',
    }
}
```

---

### 3. DEBUG

```python
DEBUG = True
```

True = Development Mode

Errors browser me dikhte hain.

```python
DEBUG = False
```

False = Production Mode

Security ke liye use hota hai.

---

### 4. SECRET_KEY

Har Django project ki ek secret security key hoti hai.

Ye project ko secure rakhne me help karti hai.

Isko kabhi bhi public nahi karna chahiye.

---

### 5. LANGUAGE_CODE

Project ki default language set karta hai.

Example

```python
LANGUAGE_CODE = "en-us"
```

---

### 6. TIME_ZONE

Project ka time zone set karta hai.

Example

```python
TIME_ZONE = "Asia/Kolkata"
```

---

### 7. STATIC_URL

CSS, JavaScript aur Images ke liye use hota hai.

Example

```python
STATIC_URL = "static/"
```

---

## Real Life Example

Socho tum mobile ki Settings open karte ho.

Wahan tum

- WiFi
- Bluetooth
- Wallpaper
- Brightness
- Sound

sab control karte ho.

Waise hi Django me settings.py project ki settings control karta hai.

---

## Meri Language

settings.py project ka setting panel hai.

Yahan se project ki almost har important setting control hoti hai.

Database kis type ka hoga.

Kaun se apps chalenge.

Language kya hogi.

Time Zone kya hoga.

Debug On ya Off hoga.

Ye sab isi file me hota hai.

---

## Interview Definition

settings.py is the main configuration file of a Django project.

It stores all important project settings such as database configuration, installed apps, security, templates, static files, language and timezone.

---

## Quick Revision

✔ Main Configuration File

✔ Database Settings

✔ Installed Apps

✔ Debug Mode

✔ Secret Key

✔ Static Files

✔ Language

✔ Time Zone

---

## One Line Revision

settings.py Django project ka Control Panel hai jahan project ki saari important settings hoti hain.
