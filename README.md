# Delete-duplicate-rows-from-DB-group-by-one-column

DELETE R1 FROM RESULT R1
JOIN RESULT R2
ON R1.CHEMISTRY_MARKS = R2.CHEMISTRY_MARKS
AND R1.MATHS_MARKS = R2.MATHS_MARKS
AND R2.STUDENT_ID < R1.STUDENT_ID;
