
# Taxi Service Web App

![](https://media.timeout.com/images/105785000/1024/576/image.jpg)

Project Description
-------------
This is a taxi service web application connected to a MySQL Database. It allows you to create, read, update, and delete data relating to cars and drivers that provide taxi services.

You must either log in to your account using your login name and password or create a new account to be able to perform the above operations.

Project Structure
-------------
A three-tier architecture-based project, this app consists of the following layers:
- Presentation tier (controllers)
- Business Logic tier (services)
- Data Tier (DAO)

Technologies Used by this Application
-------------
- Java 11
- Apache TomCat 9.0.50
- MySQL
- JDBC
- HTML, CSS
- JSP, JSTL
- Maven

Getting Started
-------------
To run this application, install MySQL and Apache TomCat 9.0.50 on your computer and follow the instructions listed below:
1. Clone this project.
2. Run the SQL scripts placed in `init_db.sql` (`resources` directory) to create a new DB schema and the respective tables.
3. Create a connection to your database in the `ConnectionUtil` class (`/taxi.util`) by using your credentials.
4. Configure TomCat. Use `/` as your application context.
5. You can now run this application by using a TomCat local server.
