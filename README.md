# Oracle APEX (Application Express)


SELECT

FROM

WHERE


SELECT descrip, qty, orderdate, name
FROM emp JOIN customer ON repid = empno
JOIN ord USING (custid)
JOIN item USING (ordid)
JOIN product USING (prodid)
WHERE ename = 'ALLEN';

