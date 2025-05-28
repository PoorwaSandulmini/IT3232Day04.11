# IT3232Day04.11
Practicals what we did at the lecture time.

Project setup with JPA entity models and MySQL configuration

- Added JPA entity classes: Employee, Department, Project
  - Employee: fields include empNo, name, age, salary, gender
  - Relationships: Many-to-One with Department, Many-to-Many with Project
  - Department: fields include dept_id, name, established; One-to-Many with Employee
  - Project: fields include id, name, totalCost; Many-to-Many with Employee

- Configured application.properties for MySQL database
  - URL: jdbc:mysql://localhost:3306/employeedb
  - Hibernate DDL: update
  - Driver: com.mysql.cj.jdbc.Driver

