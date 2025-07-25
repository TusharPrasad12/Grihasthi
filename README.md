Grihasthi.Ai 🏠
Smart PG Rental & Roommate Matching System

What is Grihasthi?
Grihasthi is a smart web platform that helps students and working professionals find PG accommodations that match their preferences. But it's more than just a listing site — Grihasthi uses AI to suggest the best PGs and even the most compatible roommates, making your house-hunting experience smoother and smarter.

Key Highlights 🚀
🔍 Search Made Easy: Look for PGs based on city, price, room type, and gender preference.

🧠 AI-Based Matching: Recommends PGs and roommates by analyzing your preferences.

🪪 Aadhaar Verification: Upload Aadhaar card images and get verified instantly with OCR.

📍 Google Maps Integration: See nearby areas before booking a PG.

👥 Three User Roles:

Admin – Manages users and properties.

Property Owner – Lists and edits PG details.

User (Renter) – Searches and books PGs.

Tech Stack 🛠️
Backend: Java Spring Boot

Frontend: HTML, CSS, JavaScript, Thymeleaf

Database: MySQL

AI/ML: Matching algorithm written in Java

Extras: Google Maps API, Tesseract OCR for Aadhaar verification

How to Run the Project 💻
Clone the project:

bash
Copy
Edit
git clone https://github.com/TusharPrasad12/grihasthi.git
Set up the backend in any IDE (like IntelliJ or Eclipse).

Create a MySQL database called grihasthi and configure it in application.properties.

Run the Spring Boot app:

bash
Copy
Edit
./mvnw spring-boot:run
Open your browser and go to http://localhost:8080

Folder Structure 📂
css
Copy
Edit
grihasthi/
├── src/
│   ├── main/java/        → Java backend
│   ├── resources/
│   │   ├── templates/    → HTML pages (Thymeleaf)
│   │   └── static/       → CSS, JS, images
├── database/             → MySQL schema
├── pom.xml               → Project dependencies
└── README.md             → You’re reading this!
 
