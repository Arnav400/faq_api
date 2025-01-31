📝 FAQ API - Built with Django & DRF
A Django-powered FAQ API designed to handle multilingual translations, offer a rich-text editor, enable Redis caching, and provide a fully functional REST API for seamless FAQ management.

🚀 Key Highlights
✅ REST API for easy FAQ management
🌍 Multilingual support via Google Translate for dynamic language switching
✍ Rich-text editing with CKEditor 5 for enhanced content formatting
⚡ Redis-based caching to speed up API responses
📝 Comprehensive unit tests to ensure API reliability and performance
🔗 API Endpoints
Method	Endpoint	Description
GET	/api/faqs/	Retrieve all FAQs
GET	/api/faqs/?lang=hi	Retrieve FAQs in Hindi
POST	/api/faqs/	Create a new FAQ
PUT	/api/faqs/{id}/	Update an existing FAQ
DELETE	/api/faqs/{id}/	Delete an FAQ
📌 Example API Calls
1. GET All FAQs
Use this endpoint to retrieve all FAQs:
GET /api/faqs/

2. GET FAQs in Hindi
Use this endpoint to retrieve FAQs in Hindi:
GET /api/faqs/?lang=hi

3. POST New FAQ
To create a new FAQ, use the POST /api/faqs/ endpoint. You’ll need to provide the FAQ content in the request body.

4. PUT (Update) FAQ
Use this endpoint to update an existing FAQ:
PUT /api/faqs/{id}/

5. DELETE FAQ
To delete a FAQ, use the DELETE /api/faqs/{id}/ endpoint.

📌 Example API Call Using Curl
To fetch FAQs in Hindi, use the following cURL command:

sh
Copy
Edit
curl http://127.0.0.1:8000/api/faqs/?lang=hi
✅ Running Unit Tests
Run the following command to execute all unit tests for the project:

sh
Copy
Edit
python manage.py test
🔧 Technologies Used
Backend: Django, Django REST Framework (DRF)
Database: SQLite (default) or PostgreSQL (optional)
Caching: Redis for performance enhancement
Editor: CKEditor 5 for rich-text FAQ content
Translation API: Google Translate for multilingual support
📜 License
This project is licensed under the MIT License. You can find more details in the LICENSE file.
