# Hospital Management System Web App

## Project Description

The Hospital Management System Web App is a comprehensive platform designed to streamline interactions between patients and doctors. It provides a user-friendly interface with functionalities such as login and registration, efficient management of doctor-patient information, and a feature to book appointments with specialists. The project utilizes Angular for the front-end, Spring Boot for the back-end, and MySQL for the database. The system includes both manual and automated testing processes to ensure functionality, integration, and system stability.

Features
User-friendly interface for both patients and doctors.
Login and registration functionality for secure access.
Appointment booking system: Patients can easily view and book appointments with available specialists.
Doctor and patient management: Efficient storage and retrieval of doctor-patient data.
Restful APIs ensure seamless communication between the front-end (Angular) and back-end (Spring Boot).
Testing: Functionality, Integration, and System Testing are implemented to guarantee stability and accuracy.
 ### **Technologies Used** <br/>
 **Frontend:** Angular <br/>
 **Backend:** Spring Boot <br/>
 **Database:** MySQL <br/>
 **Testing** Manual and Automated Testing <br/>
 **API Architecture:** RESTful APIs <br/>
## Installation and Setup Instructions

>[!IMPORTANT]
> Prerequisites:
- Node.js (for Angular)
- Angular CLI
- Java Development Kit (JDK) (Version 11+)
- MySQL
- Maven (for Spring Boot)
- Backend (Spring Boot)
### Clone the repository.
bash
Copy code:
```
git clone <repository-url>
```
Navigate to the backend project folder.
bash
Copy code:
```ruby
cd hospital-management-backend
```
Update the application.properties file with your MySQL credentials:
properties
Copy code:
```ruby
spring.datasource.url=jdbc:mysql://localhost:3306/hospital_db
spring.datasource.username=<your-username>
spring.datasource.password=<your-password>
```
Run the Spring Boot application using Maven.
bash
Copy code:
```ruby
mvn spring-boot:run
```
Frontend (Angular)
Navigate to the frontend project folder.
bash
Copy code
cd hospital-management-frontend
Install dependencies.
bash
Copy code:
```ruby
npm install
```
** Run the Angular development server. **
bash
Copy code:
```ruby
ng serve
```
Access the app in your browser.
url
Copy code:
```
http://localhost:4200
```
 ### Database Setup
Create a MySQL database named hospital_db.
sql
Copy code:
```ruby
CREATE DATABASE hospital_db;
```
The application will automatically create the required tables upon running.
API Endpoints
User (Patient/Doctor) Management
POST /api/users/register: Register a new user (patient or doctor).
POST /api/users/login: User login.
** Appointment Management **
GET /api/appointments: Get a list of available appointments.
POST /api/appointments: Book an appointment.
** Doctor-Patient Information **
GET /api/doctors: List all doctors.
GET /api/patients: List all patients.
## Testing

Functionality Testing: Ensures all features work as expected.
Integration Testing: Ensures seamless communication between frontend, backend, and database.
System Testing: End-to-end testing of the entire system.
