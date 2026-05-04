# HealthCareManagement System

##  Features

- It is a **HealthCare Management System** which can facilitate you to check your hospital status, profile information, doctor information, check slots, book doctor appointments, review the appointments, generate and print your respective prescriptions and manage the entire application.
- It has 3 modes of operation as **1) ADMIN 2) DOCTOR 3) USER**

## ADMIN Mode 
This mode makes you as an admin and you can perform various activities like...
- Adding a Doctor
- Managing Users/patients
- Managing Doctors
- Check the available Doctor Slots
- view Doctor List, Patient List, User List
- Accept or Reject the Doctors when they register as a new Doctor for this application
- Get various details on the admin dashboard as Total User, Total doctors, Total slots, Patients, Prescriptions given & Appointments booked.

## DOCTOR Mode 

This mode makes you as a doctor and you can perform various activities like...
- Dcotor can register for a new account in-order to login to the portal
- Check the available doctors List
- check the his/her today's appointments
- check his/her patient list
- View & Edit doctor profile details
- Add you available slot and check slot schedules
- check your registration approval as a valid doctor by the ADMIN
- Add new patient prescription
- Get various details on the doctor dashboard as Total Prescriptions given, Total doctors, Total slots, Patients.

## USER Mode 

This mode makes you as a user and you can perform various activities like...
- User can register for a new account in-order to login to the portal
- Check the available doctors List
- check the available slots for booking
- View & Edit user profile details
- Book a New Appoinment
- check your appointment approval by the doctor
- view your doctors prescription and print it.
- Get various details on the user dashboard as Total User, Total doctors, Total slots, Patients.

## Build 

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.


## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

# TECHNOLOGIES USED 

## Front End 

![Angular](https://img.shields.io/static/v1?style=for-the-badge&message=Angular+12&color=DD0031&logo=Angular&logoColor=FFFFFF&label=)
![HTML5](https://img.shields.io/static/v1?style=for-the-badge&message=HTML5&color=E34F26&logo=HTML5&logoColor=FFFFFF&label=)
![CSS3](https://img.shields.io/static/v1?style=for-the-badge&message=CSS3&color=1572B6&logo=CSS3&logoColor=FFFFFF&label=)
![TypeScript](https://img.shields.io/static/v1?style=for-the-badge&message=TypeScript&color=3178C6&logo=TypeScript&logoColor=FFFFFF&label=)
![jQuery](https://img.shields.io/static/v1?style=for-the-badge&message=jQuery&color=0769AD&logo=jQuery&logoColor=FFFFFF&label=)
![Bootstrap](https://img.shields.io/static/v1?style=for-the-badge&message=Bootstrap&color=7952B3&logo=Bootstrap&logoColor=FFFFFF&label=)
![JavaScript](https://img.shields.io/static/v1?style=for-the-badge&message=JavaScript&color=222222&logo=JavaScript&logoColor=F7DF1E&label=)
![Font Awesome](https://img.shields.io/static/v1?style=for-the-badge&message=Font+Awesome&color=339AF0&logo=Font+Awesome&logoColor=FFFFFF&label=)
![Material-UI](https://img.shields.io/static/v1?style=for-the-badge&message=Material-UI&color=0081CB&logo=Material-UI&logoColor=FFFFFF&label=)
![Material Design Icons](https://img.shields.io/static/v1?style=for-the-badge&message=Material+Design+Icons&color=2196F3&logo=Material+Design+Icons&logoColor=FFFFFF&label=)
![Google Fonts](https://img.shields.io/static/v1?style=for-the-badge&message=Google+Fonts&color=4285F4&logo=Google+Fonts&logoColor=FFFFFF&label=)

## Server Side 

![Spring Boot](https://img.shields.io/static/v1?style=for-the-badge&message=Spring+Boot&color=6DB33F&logo=Spring+Boot&logoColor=FFFFFF&label=)
![Java](https://img.shields.io/static/v1?style=for-the-badge&message=Java&color=DD0031&logo=Java&logoColor=FFFFFF&label=)
![Spring](https://img.shields.io/static/v1?style=for-the-badge&message=Spring+Security&color=6DB33F&logo=Spring&logoColor=FFFFFF&label=)
![Spring Boot](https://img.shields.io/static/v1?style=for-the-badge&message=Spring+Web&color=6DB33F&logo=Spring&logoColor=FFFFFF&label=)
![Spring Boot](https://img.shields.io/static/v1?style=for-the-badge&message=Spring+Data-JPA&color=6DB33F&logo=Spring&logoColor=FFFFFF&label=)
![Spring Boot](https://img.shields.io/static/v1?style=for-the-badge&message=Spring-JWT&color=222222&logo=Spring&logoColor=FFFFFF&label=)
![Hibernate](https://img.shields.io/static/v1?style=for-the-badge&message=Hibernate&color=59666C&logo=Hibernate&logoColor=FFFFFF&label=)

## Database 

![MySQL](https://img.shields.io/static/v1?style=for-the-badge&message=MySQL&color=4479A1&logo=MySQL&logoColor=FFFFFF&label=)

## How to run the project

###  Backend (Spring Boot)
```bash
cd HealthcareManagement-Backend
mvn clean install -DskipTests
mvn spring-boot:run
```
Runs at: http://localhost:8080

---

### Frontend (Angular)
```bash
cd HealthcareManagement
npm install --legacy-peer-deps
set NODE_OPTIONS=--openssl-legacy-provider   # Optional (for OpenSSL issues)
npm start
```
Runs at: http://localhost:4200

---

### Database (MySQL)
```sql
CREATE DATABASE health_db;
```

Update `application.properties`:
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/health_db
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
```

---

###  Access the Application
- Frontend → http://localhost:4200  
- Backend API → http://localhost:8080  
- Database → MySQL (`health_db`)

---

### Prerequisites
- Java JDK 17  
- Maven  
- Node.js (14–18)  
- Angular CLI 12  
- MySQL 8  

> Ensure backend is running before starting frontend.


