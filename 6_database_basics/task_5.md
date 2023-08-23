The query you were able to solve the problem with

```sql
SELECT 
	transactions.id_transaction AS id_transaction,
    products.category AS category,
    products.name AS name
    
FROM
	transactions
INNER JOIN products ON products.id_product = transactions.id_product
ORDER BY 
id_transaction ASC
LIMIT 	10
```
