- First create a database called BloodBank
- Then create a table called Donors
- Make sure you have the [JDBC connector in the project](https://dev.mysql.com/downloads/connector/j/)

Commands to create the database and table
```
CREATE DATABASE BloodBank;
USE BloodBank;
CREATE TABLE Donors (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(255),
    blood_group VARCHAR(10)
);

```