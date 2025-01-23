sqlite3 baseball.sqlite3

.schema
.mode columns
.headers on
.read SQL_FILENAME
.quit

SELECT    _______
FROM      _______, _______
INNER JOIN _______ ON primary key = foreign key
WHERE     _______
AND       _______
GROUP BY  _______
ORDER BY  _______ (DESC)
LIMIT     _______;

```
< > = <= >=
COUNT(*)
SUM(_), AVG(_), MAX(_), MIN(_)
```
