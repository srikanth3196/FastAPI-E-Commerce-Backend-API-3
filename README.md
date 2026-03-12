# FastAPI-E-Commerce-Backend-API-3
A simple E-Commerce Backend API built with FastAPI
The API supports product management, filtering, comparison, order placement, inventory auditing, and bulk discounts.
This project demonstrates core backend concepts such as:
REST API design,CRUD operations,Data validation with Pydantic,Query parameters,Inventory management logic,FastAPI routing rules
Swagger API documentation
🚀 Features
Product Management
View all products
Get a product by ID
Add new products
Update price or stock status
Delete products
Product Utilities
Filter products by category, price, or stock
Compare two products
Inventory audit summary
Apply bulk discounts to a category
Orders
Place customer orders
View all placed orders

⚙️ Tech Stack
Technology	Purpose
Python	Core programming language
FastAPI	Backend API framework
Pydantic	Data validation
Uvicorn	ASGI server
Swagger UI	Interactive API docs

Install dependencies:
pip install fastapi uvicorn
Run the server:
uvicorn main:app --reload

📚 API Documentation

FastAPI automatically generates interactive documentation.

Open in your browser:

Swagger UI

http://127.0.0.1:8000/docs


📌 Available Endpoints
General
Method	Endpoint	Description
GET	/	API welcome message
Products
Method	Endpoint	Description
GET	/products	Get all products
GET	/products/{product_id}	Get single product
GET	/products/filter	Filter products
GET	/products/compare	Compare two products
GET	/products/audit	Inventory summary
POST	/products	Add new product
PUT	/products/{product_id}	Update product
PUT	/products/discount	Apply category discount
DELETE	/products/{product_id}	Delete product
Orders
Method	Endpoint	Description
POST	/orders	Place an order
GET	/orders	View all orders

🧠 Concepts Demonstrated
This project practices important backend concepts:
REST API development
CRUD operations
Request validation with Pydantic
Query parameters
Business logic separation
FastAPI routing rules
API documentation
Inventory calculations
