
✈️ Airline Reservation System (Java + MySQL)

A complete Airline Reservation System built using Java Swing, JDBC, and MySQL.
This project allows users to manage customers, flights, and ticket bookings through a simple GUI.


🚀 Features

👤 Customer Management

Add new customers with full details

Search and view customer information by Customer ID

Update or edit customer records

🛫 Flight Management

Add new flights with details like source, destination, date, and fare

Search flights by source, destination, or date

Update flight information

🔐 Admin Management

Add new admin accounts

Auto-generate unique Admin IDs

Manage admin credentials securely

🎫 Ticket Booking

Book tickets for registered customers

Auto-generate unique Ticket IDs

Calculate total fare based on number of seats

View booked tickets and details


🛠 Tech Stack

Java (Swing GUI)

MySQL Database

JDBC

NetBeans IDE


🗄️ Database Setup (MySQL)
1️⃣ Create the database
CREATE DATABASE airline_project;

2️⃣ Import the SQL file

Import airline_project.sql from the database folder into your MySQL database.

3️⃣ Update Database Connection

Before running the project, update your MySQL username and password:

Connection conn = DriverManager.getConnection(
    "jdbc:mysql://localhost:3306/airline_project", 
    "your_mysql_username", 
    "your_mysql_password"
);


⚠️ Important:
Replace your_mysql_username and your_mysql_password with your own MySQL credentials.

▶️ How to Run
1️⃣ Clone the repository
git clone https://github.com/Jasbe04/AirlineReservationSystem.git



🔹 Replace your-username with your GitHub username.


2️⃣ Open the project in NetBeans
3️⃣ Ensure MySQL Server is running
4️⃣ Update the database username & password in the code
5️⃣ Run the project from:
Main.java

📸 Screenshots

### Login Page
<img width="989" height="534" alt="image" src="https://github.com/user-attachments/assets/f12eaae3-39bc-4a30-8043-ae0559fbe2d9" />

### Add Customer
<img width="1141" height="853" alt="image" src="https://github.com/user-attachments/assets/2e156a9b-fc1b-4968-84ac-17d56b23014f" />

### Search Customer
<img width="1151" height="849" alt="image" src="https://github.com/user-attachments/assets/1f0887ab-e710-43b9-ae12-9f6f7a1f6232" />

### Add Flight
<img width="1145" height="853" alt="image" src="https://github.com/user-attachments/assets/ef982bec-7dec-4263-92a1-c1c580f29d11" />

### Book Flight
<img width="1153" height="846" alt="image" src="https://github.com/user-attachments/assets/964d95e2-2efd-4d7e-8421-f6a5c737e85e" />

### Get Ticket
<img width="1134" height="850" alt="image" src="https://github.com/user-attachments/assets/cd1a6ac8-8152-49a9-a7d9-d9d6324d3fd3" />

### Add Admin
<img width="1147" height="851" alt="image" src="https://github.com/user-attachments/assets/5c48a5c1-3516-4987-968a-8c48da326976" />

📌 Future Improvements

Ticket cancellation system

Generate printable e-ticket (PDF)

Improve Swing UI design

🤝 Contributing

Pull requests are welcome.
For major changes, please open an issue first.

📄 License

This project is open-source under the MIT License.
