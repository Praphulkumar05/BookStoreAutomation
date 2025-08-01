# BookStoreAutomation
API Testing Project using Postman and Defect Report


📘 Bookstore API Testing Project
📅 Date: August 1, 2025
🧪 Tested Using: Postman
🔍 Defect Tracking: Excel (simulated)
🔧 Project Overview
This project involves manual API testing of a Bookstore Management System using Postman. The API provides endpoints for managing book inventory, user actions, and order processing.

The objective of this project was to validate the correctness and performance of REST endpoints under various scenarios.
GET /books → Fetch all books

POST /books → Add a new book

GET /books/:id → Get book by ID

PUT /books/:id → Update book

DELETE /books/:id → Delete book

POST /login → Login user

POST /order → Place an order

✅ Test Scenarios Covered
Status Code verification

Response Time validation

Response Body schema check

Authentication and Authorization

Negative testing with invalid data

🐞 Defect Reporting
ID	Endpoint	Request Type	Severity	Expected Result	Actual Result	Status
101	/books/9999	GET	Medium	404 Not Found	200 OK (with null)	Open
102	/order	POST	High	Order placed	500 Server Error	Open

📝 For full list, see Defect_Report.xlsx.

🛠️ Tools Used
Postman for API request automation

Git & GitHub for version control

Excel for Defect Tracking

📤 How to Run This
Import Bookstore_API_Collection.json into Postman.

Use environment variables for base URL and tokens.

Click Run Collection in Postman Collection Runner.

Review responses and match against expected outputs.

📈 Results
Majority of endpoints passed positive and negative tests.

2 simulated defects recorded for documentation.

🧾 License
This project is for educational/demo purposes only.

✅ Next Steps
 Add Test Cases using Java + RestAssured

 Automate Postman test cases using Newman
