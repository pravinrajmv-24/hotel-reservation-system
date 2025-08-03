Hotel Reservation System (Java + Hibernate + MySQL)

A console-based hotel booking application that allows admins to manage hotel rooms, customers, and room bookings using **Java**, **Hibernate ORM**, and **MySQL**.

Folder Structure

HotelReservationSystem/
├── src/
│   └── com/hrs/
│       ├── Booking.java
│       ├── Customer.java
│       ├── Room.java
│       ├── HotelDAO.java
│       └── MainApp.java
├── resources/
│   └── hibernate.cfg.xml
├── pom.xml

Technologies Used

* Java
* Hibernate 6.4.4.Final
* MySQL
* JDK 8+
* Maven
* Jakarta Persistence API

Features

* Add new rooms
* Register new customers
* Book available rooms
* View available rooms
* View all bookings
* Cancel existing bookings
* Update booking dates

Setup Instructions

1. Clone the Project

git clone https://github.com/your-repo/hotel-reservation-system.git
cd hotel-reservation-system

2. MySQL Setup

* Create a database called `hotel`

sql
CREATE DATABASE hotel;


* Update your credentials in `hibernate.cfg.xml`:
xml
<property name="hibernate.connection.username">root</property>
<property name="hibernate.connection.password">your_password</property>


3. Build with Maven

mvn clean install


4. Run the Application

java -cp target/Hotel_Reservation_System-0.0.1-SNAPSHOT.jar com.hrs.MainApp


Example Usage

----- HOTEL BOOKING/RESERVATION SYSTEM -----
1) ADD ROOM
2) ADD CUSTOMER
3) BOOK ROOM
4) VIEW AVAILABLE ROOMS
5) VIEW ALL BOOKINGS
6) CANCEL BOOKING
7) UPDATE BOOKING
8) EXIT

Sample Hibernate Configuration

```xml
<property name="hibernate.dialect">org.hibernate.dialect.MySQLDialect</property>
<property name="hibernate.hbm2ddl.auto">update</property>
<property name="hibernate.show_sql">false</property>
```

Would you like me to create a downloadable `.md` file version of this too?
