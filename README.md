# 📚 Library Management System API

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-6.1-green.svg)](https://www.djangoproject.com/)
[![DRF](https://img.shields.io/badge/Django--REST--Framework-Latest-red.svg)](https://www.django-rest-framework.org/)

---

## English Description

### Overview
This project is a comprehensive *RESTful API* for a digital Library Management System, built using *Python, **Django, and **Django REST Framework*. The system streamlines the management of books, authors, and categories, featuring a customized and branded Admin Dashboard alongside secure authentication using JWT Bearer Tokens.

### Key Features
* *Custom Admin Dashboard:* Branded "Purple & Gold" visual theme for the Django Admin interface using django-admin-interface.
* *RESTful API Endpoints:* Full CRUD (Create, Read, Update, Delete) functionality for Books, Authors, and Categories.
* *Security & Authentication:* Endpoint authentication and authorization implemented via JWT Bearer Tokens using djangorestframework-simplejwt.
* *Static & Dynamic Asset Management:* Proper static files configuration and collection setup for production readiness.

### Tech Stack & Tools
* *Backend Framework:* Python / Django / Django REST Framework (DRF)
* *Authentication:* SimpleJWT (JWT Bearer Tokens)
* *Admin Customization:* django-admin-interface
* *Database:* SQLite (Development)
* *Development Environment:* PyCharm IDE
* *API Testing:* Postman
* *Version Control:* Git & GitHub

### Database Models
1. *Books:* Title, Author, Category, Publication Date, ISBN, Description.
2. *Authors:* Name, Bio, Birth Date.
3. *Categories:* Category Name, Description.

### How to Run Locally
```bash
# 1. Clone the repository
git clone [https://github.com/YOUR_USERNAME/Library_project.git](https://github.com/YOUR_USERNAME/Library_project.git)

# 2. Navigate into the project directory
cd Library_project

# 3. Activate Virtual Environment (Windows)
.venv\Scripts\activate

# 4. Install dependencies
pip install -r requirements.txt

# 5. Apply database migrations
python manage.py migrate

# 6. Run the development server

نبذة عن المشروع
هذا المشروع عبارة عن واجهة برمجية متكاملة (RESTful API) لنظام إدارة مكتبة رقمية، تم تطويره باستعمال لغة Python وإطار العمل Django مع Django REST Framework. يهدف النظام إلى تسهيل إدارة بيانات المكتبة من كتب ومؤلفين وتصنيفات، مع توفير لوحة تحكم مخصصة ومحمية بهوية بصرية مميزة، ودعم التوثيق والأمان المتقدم عبر JWT Tokens.
المميزات الرئيسية
 لوحة تحكم مخصصة: تصميم وتعديل الهوية البصرية للوحة الأدمن باللونين البنفسجي والذهبي باستخدام django-admin-interface.
 واجهات برمجية متكاملة: دعم كامل لجميع عمليات (CRUD: إنشاء، قراءة، تحديث، حذف) للكتب والمؤلفين والفئات.
 أدوات تحويل وفحص البيانات (Serializers): معالجة التحقق من صحة البيانات المرسلة وتجهيزها بصيغة JSON.
 الأمان والتوثيق: تأمين الواجهات البرمجية وحماية العمليات باستخدام JWT (JSON Web Tokens) و Bearer Tokens عبر djangorestframework-simplejwt.
 إدارة الملفات الثابتة: تهيئة وإدارة الملفات الثابتة (STATIC_ROOT) وجمعها بنجاح عبر collectstatic.
التقنيات والأدوات المستخدمة
 إطار العمل الخلفي: Python / Django / Django REST Framework
 التوثيق والحماية: SimpleJWT
 تخصيص لوحة التحكم: django-admin-interface
 قواعد البيانات: SQLite
 بيئة التطوير: PyCharm IDE
 اختبار الـ APIs: Postman
 إدارة النسخ: Git & GitHub
هيكلية البيانات
1. الكتب: العنوان، المؤلف، التصنيف، تاريخ النشر، الرقم المعياري ISBN، الوصف.
2. المؤلفون: الاسم، السيرة الذاتية، تاريخ الميلاد.
3. التصنيفات: اسم التصنيف، الوصف.

طريقة التشغيل محلياً

# 1. استنساخ المستودع
git clone [https://github.com/YOUR_USERNAME/Library_project.git](https://github.com/YOUR_USERNAME/Library_project.git)

# 2. الانتقال إلى مجلد المشروع
cd Library_project

# 3. تفعيل البيئة الوهمية
.venv\Scripts\activate

# 4. تثبيت المكتبات المطلوبة
pip install -r requirements.txt

# 5. تطبيق الهجرات وقواعد البيانات
python manage.py migrate

# 6. تشغيل السيرفر المحلي
python manage.py runserver