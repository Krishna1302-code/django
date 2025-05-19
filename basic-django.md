#### 13th may Tuesday 
## 📌 What is Django?

Django is a **Python-based web framework** that helps you build **websites and web applications** quickly, cleanly, and securely.
---
#### In other words, Imagine Django as a cooking recipe kit that gives you all the ingredients (database, authentication, forms, etc.) needed to cook a delicious web application. You don’t need to find each ingredient separately—Django provides everything to make development fast, secure, and efficient.



Think of it like a **toolbox** with everything you need to:
- Create websites
- Handle users (login/signup)
- Connect to databases
- Show pages (HTML)
- Build APIs
- Upload files/images

---
## 🌍 Website vs Web Application

### 🔄 Comparison Table

| Type          | Example             | What It Does                                                               |
|---------------|---------------------|----------------------------------------------------------------------------|
| ✅ Website     | Wikipedia           | Just shows information, mostly read-only                                   |
| ✅ Website     | Portfolio Site      | Static info like projects, contact form                                    |
| ✅ Website     | News Site (BBC, NDTV) | Reads articles, minimal interactivity                                   |
| ✅ Web App     | Instagram           | User login, upload photos, comment, follow                                |
| ✅ Web App     | Amazon              | Shopping, user accounts, payments, tracking orders                         |
| ✅ Web App     | Gmail               | Email service – sending, receiving, organizing emails                      |
| ✅ Web App     | Online Banking      | Login, check balance, transactions, statements                             |

### ✅ Summary:
> A **website** gives info.  
> A **web application** lets users **interact**, do tasks like login, upload, buy, comment, etc.

---
## 🧠 Django’s Architecture – MTV

Django uses a structure similar to MVC, called **MTV**:

| Part      | Meaning                  | File Used       |
|-----------|--------------------------|-----------------|
| **Model** | Defines data (DB tables) | `models.py`     |
| **Template** | How the website looks     | `.html` files    |
| **View**  | Logic for handling request | `views.py`      |

---
## 🚀 Real-world Examples of Django Use

- **Instagram** – image sharing, feed, comments
- **Pinterest** – saving images to boards
- **Mozilla** – uses Django for internal tools
- **NASA**, **Disqus**, **Spotify** – also use Django in parts

---
## ⚙️ Built-in Features of Django (In Simple Words)

Django gives you **pre-built tools** to avoid writing everything from scratch.

### 🔧 Core Features

1. **Admin Panel**
   - Auto dashboard to manage content (CRUD)

2. **ORM (Object Relational Mapper)**
   - Work with database using Python (no SQL)

3. **URL Routing**
   - Connect URLs like `/home`, `/profile` to your logic

4. **Templates**
   - Dynamic HTML pages with Python variables

5. **Authentication System**
   - Built-in login, logout, registration, password management

6. **Form Handling**
   - Create and validate forms easily (sign up, contact forms, etc.)

7. **Security**
   - Protection from CSRF, XSS, SQL injection by default

8. **Testing Tools**
   - Test if your code works correctly (unit tests)

9. **Middleware**
   - Add custom checks (e.g., check if user is logged in) between request and response

10. **Internationalization (i18n)**
    - Supports multiple languages

---

## 🧩 Summary

> Django = All-in-one Python framework for building fast, secure, scalable web apps with less code.

---
# MVT in Django
#### The key concept in Django is how it is structured and how it handles requests from users. To break things down simply, Django follows a pattern called MVT (Model-View-Template), which is a variation of the popular MVC (Model-View-Controller) pattern.

