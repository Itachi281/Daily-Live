# dailylive-backend
# Project Setup Guide
# *Version Java 17and spring Boot also 3.1

## *I am using Swager dependency for checking endpoints throug UI ;
## Step 1: Pull Files
Firstly, pull file from the repository.


## Step 3: Open Backend in IntelliJ
Similarly, open the backend code in IntelliJ IDEA.

## Step 4: Create Database in MySQL
Create a database named "dailyLiveApp" in MySQL.

## Step 5: Set Up and Run
After completing the above steps, set up any necessary configurations and directly run the project in IntelliJ.



##  for database
spring.datasource.url=jdbc:mysql://localhost:3306/customer
spring.datasource.driverClassName=com.mysql.cj.jdbc.Driver
spring.datasource.username=enter your user_name
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
spring.h2.console.enabled=true

## Production URL
http://46.28.44.46:8081/
