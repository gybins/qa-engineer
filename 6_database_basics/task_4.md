The query you were able to solve the problem with

```sql
SELECT cabs.company_name, COUNT(trips.cab_id) as trips_amount 
FROM trips 
INNER JOIN cabs ON cabs.cab_id = trips.cab_id 
WHERE start_ts >= '2017-11-15 00:00' AND start_ts <= '2017-11-16 23:59' 
GROUP BY company_name 
ORDER BY trips_amount DESC
```
