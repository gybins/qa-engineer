The query you were able to solve the problem with
> SELECT ts AS ts,
CASE
> WHEN description LIKE '%rain%' THEN 'Bad' 
WHEN description LIKE '%storm%' THEN 'Bad' 
ELSE 'Good' END AS weather_conditions
FROM weather_records 
WHERE ts >= '2017-11-05 00:00' AND ts <= '2017-11-06 00:00'; 
