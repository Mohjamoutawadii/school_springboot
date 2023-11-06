# Spring Boot Project Setup Guide

This guide will help you set up and run a Spring Boot project using Eclipse, Maven, and MySQL database configuration.

## Prerequisites

- Java Development Kit (JDK) installed (recommended version 8 or later)
- Eclipse IDE installed
- MySQL installed on your machine

## Steps to Run the Project

1. **Clone the Project Repository**
2. **Open the Project in Eclipse**
Open Eclipse and import the project:
`File -> Import -> Existing Maven Projects` and select the root directory of the cloned project.

3. **Database Configuration**
create a databse in mysql called school
Update the application.properties file in the project:
spring.datasource.username=your_username
spring.datasource.password=your_password
4. **Run the project**
   Go to package demo -> school1application.java -> right click -> run as a java application
   
