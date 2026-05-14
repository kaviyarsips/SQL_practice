-- COUNT
SELECT COUNT(*) FROM Student;

-- MAX
SELECT MAX(mark) FROM Marks;

-- MIN
SELECT MIN(mark) FROM Marks;

-- AVG
SELECT AVG(mark) FROM Marks;

-- SUM
SELECT SUM(mark) FROM Marks;

-- GROUP BY
SELECT dept, COUNT(*)
FROM Student
GROUP BY dept;

-- GROUP BY with AVG
SELECT dept, AVG(mark)
FROM Marks
GROUP BY dept;

-- HAVING Clause
SELECT dept, COUNT(*)
FROM Student
GROUP BY dept
HAVING COUNT(*) > 1;

-- ORDER BY with Aggregate
SELECT dept, AVG(mark)
FROM Marks
GROUP BY dept
ORDER BY AVG(mark) DESC;

-- Aggregate with WHERE
SELECT COUNT(*)
FROM Student
WHERE dept='AI';

-- Multiple Aggregates
SELECT
MAX(mark),
MIN(mark),
AVG(mark),
SUM(mark)
FROM Marks;
