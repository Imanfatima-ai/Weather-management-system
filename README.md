# Weather-management-system
OOP-based weather system in C++ with API integration

##  Overview
The **Weather Management System** is a console-based application developed in **C++ using Object-Oriented Programming (OOP)**.  
It provides real-time weather updates, forecasts, and data management features using the **OpenWeatherMap API**, along with offline cached data support.

---

##  Project demo video
[watch demo video]
https://drive.google.com/file/d/1l3PsZVna22AOjhEqx2nEd475maA95jdV/view?usp=sharing


##  Features
### User Features
- View real-time weather of any city  
- View 5-day weather forecast  
- Manage favourite cities  
- Compare weather between two cities  

###  Authentication
- User registration & login  
- Basic password encryption  
- File-based user storage  

###  Admin Features
- View all weather data  
- Manage users (delete/reset password)  
- Manage API/data sources  
- Generate historical reports  
- Access system settings  

###  System Features
- Real-time API integration  
- File handling (data persistence)  
- Auto-save functionality  
- Temperature unit conversion (Celsius/Fahrenheit)  
- Cache clearing  

---

##  OOP Concepts Used
- **Encapsulation**  
- **Inheritance** (Admin inherits from User)  
- **Polymorphism** (virtual functions)  
- **Abstraction**  

---

##  Project Structure    
Weather-Management-System/
├── main.cpp
├── weather_data.txt
├── forecast_data.txt
├── users.txt
├── system_settings.txt
└── README.md

---

##  Technologies Used
- C++ (C++17)  
- OpenWeatherMap API  
- File Handling  
- curl (for API requests)  

---

 Learning Outcomes
Implementation of OOP concepts
API integration in C++
File handling & data persistence
Role-based system design

Limitations
Basic password encryption (not secure)
Console-based UI
Uses system curl instead of native HTTP library


Author
Iman Fatima
BS AI – 2nd Semester
