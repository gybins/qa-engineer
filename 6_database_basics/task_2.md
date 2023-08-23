The query you were able to solve the problem with

```sql
chicago_taxi=#
SELECT COUNT(cab_id) AS cnt, company_name AS company_name
FROM cabs
GROUP BY company_name
HAVING COUNT(cab_id) < 100
ORDER BY cnt DESC;
```
