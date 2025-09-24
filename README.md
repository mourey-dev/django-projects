# Django Projects Practice

This repository contains multiple Django practice projects.  
Each project is developed in a **separate branch** for better isolation and learning.

---

## 📌 Projects Roadmap

### 1. ✅ Todo App (`todo-app` branch)

- **Goal:** Practice the basics of Django
- **Django Features:**
  - Models (`Task`)
  - CRUD (Create, Read, Update, Delete)
  - Templates & Template Inheritance
  - Forms (`ModelForm`)
  - URL routing & function-based views

---

### 2. Blog App (`blog-app` branch)

- **Goal:** Learn relationships and template organization
- **Django Features:**
  - Models (`Post`, `Comment`)
  - One-to-Many relationships
  - Admin customization
  - Template inheritance (`base.html`)
  - Pagination with `Paginator`

---

### 3. Notes with Authentication (`notes-auth-app` branch)

- **Goal:** Work with users and permissions
- **Django Features:**
  - User authentication (login, logout, signup)
  - Model relationships (`User` → `Note`)
  - Permissions (only owner can edit/delete)
  - Messages framework
  - Class-based views (`ListView`, `DetailView`, `CreateView`)

---

### 4. Messaging App (`messaging-app` branch)

- **Goal:** Learn foreign keys and filtering queries
- **Django Features:**
  - Models (`User`, `Message`)
  - ForeignKey relationships
  - Query filtering (`filter`, `exclude`)
  - Django forms (`ModelForm`)
  - Bootstrap/Tailwind integration

---

### 5. Polls App (`polls-app` branch)

- **Goal:** Build a voting system
- **Django Features:**
  - Models (`Poll`, `Choice`, `Vote`)
  - Relationships (Many-to-One)
  - Forms with radio buttons
  - Handling POST requests
  - Aggregation queries (vote counts)

---

### 6. File Upload App (`file-upload-app` branch)

- **Goal:** Handle media files in Django
- **Django Features:**
  - FileField / ImageField
  - MEDIA_URL & MEDIA_ROOT
  - File upload forms
  - Serving files in development
  - Access restrictions (owner-only files)

---

### 7. Mini E-commerce Store (`mini-store` branch)

- **Goal:** Combine everything into a more complex app
- **Django Features:**
  - Models (`Product`, `Order`, `OrderItem`)
  - Many-to-Many through relationships
  - Sessions (shopping cart)
  - Authentication (checkout requires login)
  - Admin management for products/orders

---

## 🚀 Workflow

- Each project lives in its **own branch**.
- Start new project:
  ```bash
  git checkout main
  git checkout -b <project-branch>
  ```
