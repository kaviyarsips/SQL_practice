-- INNER JOIN
SELECT Student.name, Marks.mark
FROM Student
INNER JOIN Marks
ON Student.id = Marks.id;

-- LEFT JOIN
SELECT Student.name, Marks.mark
FROM Student
LEFT JOIN Marks
ON Student.id = Marks.id;

-- RIGHT JOIN
SELECT Student.name, Marks.mark
FROM Student
RIGHT JOIN Marks
ON Student.id = Marks.id;

-- FULL OUTER JOIN
SELECT Student.name, Marks.mark
FROM Student
FULL OUTER JOIN Marks
ON Student.id = Marks.id;

-- JOIN with WHERE
SELECT Student.name, Marks.mark
FROM Student
INNER JOIN Marks
ON Student.id = Marks.id
WHERE Marks.mark > 80;

-- JOIN with ORDER BY
SELECT Student.name, Marks.mark
FROM Student
INNER JOIN Marks
ON Student.id = Marks.id
ORDER BY Marks.mark DESC;

-- Multiple Table JOIN
SELECT Student.name, Marks.mark, Department.dept_name
FROM Student
INNER JOIN Marks
ON Student.id = Marks.id
INNER JOIN Department
ON Student.id = Department.id;

-- SELF JOIN
SELECT A.name AS Student1, B.name AS Student2
FROM Student A, Student B
WHERE A.id <> B.id;

-- CROSS JOIN
SELECT Student.name, Department.dept_name
FROM Student
CROSS JOIN Department;
