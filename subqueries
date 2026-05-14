-- Subquery using IN
SELECT name
FROM Student
WHERE id IN (
    SELECT id
    FROM Marks
    WHERE mark > 80
);

-- Subquery using EXISTS
SELECT name
FROM Student
WHERE EXISTS (
    SELECT *
    FROM Marks
    WHERE Student.id = Marks.id
);

-- Subquery using MAX
SELECT name
FROM Student
WHERE id = (
    SELECT id
    FROM Marks
    WHERE mark = (
        SELECT MAX(mark)
        FROM Marks
    )
);

-- Subquery with AVG
SELECT id, mark
FROM Marks
WHERE mark > (
    SELECT AVG(mark)
    FROM Marks
);

-- Nested Subquery
SELECT name
FROM Student
WHERE id IN (
    SELECT id
    FROM Marks
    WHERE mark IN (
        SELECT mark
        FROM Marks
        WHERE mark > 70
    )
);

-- Subquery with NOT IN
SELECT name
FROM Student
WHERE id NOT IN (
    SELECT id
    FROM Marks
);

-- Correlated Subquery
SELECT name
FROM Student S
WHERE EXISTS (
    SELECT *
    FROM Marks M
    WHERE S.id = M.id
    AND M.mark > 75
);
