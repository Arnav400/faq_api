📝 FAQ API - Django & DRF
A Django-powered FAQ API with multilingual support, a rich-text editor, Redis caching, and a fully functional REST API for seamless FAQ management.

🚀 Features
✅ REST API for managing FAQs
🌍 Multilingual support via Google Translate
✍ Rich-text editing with CKEditor 5
⚡ Fast caching using Redis
📝 Unit tests for reliability
🔗 API Endpoints
Method	Endpoint	Description
GET	/api/faqs/	Retrieve all FAQs
GET	/api/faqs/?lang=hi	Retrieve FAQs in Hindi
POST	/api/faqs/	Create a new FAQ
PUT	/api/faqs/{id}/	Update an FAQ
DELETE	/api/faqs/{id}/	Delete an FAQ
📌 Example API Call
Fetch FAQs in Hindi using:

sh
Copy
Edit
curl http://127.0.0.1:8000/api/faqs/?lang=hi
✅ Running Tests
Run all unit tests:

sh
Copy
Edit
python manage.py test
🔧 Tech Stack
Backend: Django, DRF
Database: SQLite/PostgreSQL
Caching: Redis
Editor: CKEditor 5
Translation API: Google Translate
📜 License
Licensed under the MIT License. See LICENSE for details. 🚀
