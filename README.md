# Answers.sql
sql
CREATE TABLE student (
    id INT PRIMARY KEY,       -- Integer type for id with primary key constraint
    fullName VARCHAR(100),    -- Text field for full name with a maximum of 100 characters
    age INT                   -- Integer type for age
);



sql
INSERT INTO student (id, fullName, age)
VALUES 
(1, 'John Doe', 18),
(2, 'Jane Smith', 20),
(3, 'Samuel Adams', 22);


sql
UPDATE student
SET age = 20
WHERE id = 2;
