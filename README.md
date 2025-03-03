# **Air-Booking-NTier-WebAPIs**  

A robust **Air Booking System** built using **N-Tier Architecture** and **Web APIs**, ensuring scalability, security, and maintainability.  

## **📌 Features**  
✅ **N-Tier Architecture** (Presentation, Business Logic, Data Layer)  
✅ **RESTful Web APIs** for handling booking operations  
✅ **Flight & Seat Availability Management**  
✅ **Guest Management & Secure Bookings**  
✅ **Payment Integration (Stripe)**  
✅ **MSSQL Database with Stored Procedures**  
✅ **Authentication & Authorization**  

## **🛠️ Tech Stack**  
- **Frontend**: ASP.NET MVC, HTML, CSS, JavaScript  
- **Backend**: ASP.NET Web API  
- **Database**: MS SQL Server  
- **Payment Gateway**: Stripe  
- **Architecture**: N-Tier Architecture   

## **📂 Project Structure**  
```
/Air-Booking-NTier-WebAPIs 
│── APIs # Web API layer 
│── Repositories # Data Access Layer 
│── AirBooking # MVC Frontend 
│── SharedModels # Shared Models 
│── SQL_Scripts # Database scripts & stored procedures 
│── README.md # Documentation 
│── ARCHITECTURE.jpg # N-Tier explanation with diagrams
```

## **🚀 Setup Instructions**  
1. Clone the repository:  
   ```sh
   git clone https://github.com/your-username/Air-Booking-NTier-WebAPIs.git
2. Open the solution in Visual Studio.
3. Configure appsettings.json with your database connection string.
4. Run database migrations or execute SQL scripts.
5. Start the API project and then the MVC UI project.
6. Test APIs via Postman or Swagger.
