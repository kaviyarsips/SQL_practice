-- PRIMARY KEY
CREATE TABLE Employee(
    emp_id INT PRIMARY KEY,
    emp_name VARCHAR(50)
);

-- NOT NULL
CREATE TABLE Student(
    id INT,
    name VARCHAR(50) NOT NULL
);

-- UNIQUE
CREATE TABLE Users(
    email VARCHAR(100) UNIQUE
);

-- DEFAULT
CREATE TABLE Product(
    quantity INT DEFAULT 1
);

-- CHECK Constraint
CREATE TABLE AgeCheck(
    age INT CHECK(age >= 18)
);

-- FOREIGN KEY
CREATE TABLE Orders(
    order_id INT,
    emp_id INT,
    FOREIGN KEY(emp_id)
    REFERENCES Employee(emp_id)
);

-- AUTO_INCREMENT
CREATE TABLE Customer(
    customer_id INT AUTO_INCREMENT PRIMARY KEY,
    customer_name VARCHAR(50)
);

-- Composite Primary Key
CREATE TABLE Attendance(
    student_id INT,
    subject_id INT,
    PRIMARY KEY(student_id, subject_id)
);

-- Constraint with INSERT
INSERT INTO Employee VALUES(1,'Ram');

-- DEFAULT example
INSERT INTO Product VALUES();
