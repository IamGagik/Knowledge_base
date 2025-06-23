______

# 📚 Internal Knowledge Base Platform

A **Django-powered internal platform** for managing and sharing knowledge across the company.

> 🚧 This project runs on the company's internal VPN.  
> 🔐 The source code is not publicly accessible — only screenshots are provided below.

---

## ✨ Key Features

- 📝 **Articles**: create, edit, browse structured learning materials  
- 🎓 **Courses**: add full course cards with price, tags, and ratings  
- ⭐ **Feedback & Ratings**: employees leave reviews (1–5 stars) with comments  
- 🏷 **Fixed Tags**: Development, Testing, Design, DevOps, Marketing/Management, Sales  
- 🔍 **Filter & Search**: by tags and categories  
- 📥 **Drag-and-drop File Upload**: with AJAX deletion of attachments  
- 🧑‍💼 **Role System**:
  - Authenticated users can write articles & upload courses
  - Anonymous users can view only
- 📄 **CKEditor**: for rich text formatting  
- 🧭 **Navigation**:
  - Home — latest articles
  - Courses — filtered with rating and category
  - Articles — grouped by tags

---

## 🌐 Access & VPN Note

> The platform is hosted **on a company server** and accessible **only via internal VPN**.  
> The backend and database are not exposed externally.

Therefore, source code is not provided in this repository —  
only **screenshots** of the user interface and admin panel are included.

---

## 🔧 Tech Stack

- **Python 3.11**
- **Django 4.2**
- **PostgreSQL**
- **Django CKEditor**
- **Django-taggit**
- **django-filter**
- **BeautifulSoup / requests** (for article import from Habr)
- **gunicorn + Whitenoise** (for deployment)
- **Docker** (optional for local setup)

---

## 📂 Project Structure (Overview)

```text
knowledge_base/
├── articles/          # Articles app (with CKEditor)
├── courses/           # Courses app with ratings and feedback
├── users/             # Auth system with roles
├── attachments/       # Drag-and-drop file handling
├── core/              # Base templates and static structure
├── manage.py
└── requirements.txt
```

---

## 📸 Screenshots

> Below are screenshots of key parts of the platform, as the code is private.
<img width="1440" alt="Снимок экрана 2025-06-21 в 13 58 17" src="https://github.com/user-attachments/assets/44f1787a-5742-4302-9f63-c2c9bf686828" />
<img width="1440" alt="Снимок экрана 2025-06-21 в 13 58 34" src="https://github.com/user-attachments/assets/fa23bcfa-15fb-4b42-b644-6cc72c562a74" />
<img width="1440" alt="Снимок экрана 2025-06-18 в 13 40 31" src="https://github.com/user-attachments/assets/0f453efe-5c7e-45d6-bb5e-439001c2d13b" />

---

## 👨‍💻 Author

Gagik Abrahamyan  
📧 abraamyangagik10@gmail.com  
🐙 [github.com/IamGagik](https://github.com/IamGagik)

______
