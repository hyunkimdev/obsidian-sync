SQL은 Structured Query Language의 약자입니다. 데이터베이스에서 데이터를 관리하는 데 사용됩니다.

## 관련 노트
- [[API]]: API를 통해 데이터베이스와 상호작용할 때 자주 사용됩니다.
- [[REST API]]: REST API를 통해 데이터베이스와 상호작용할 때 자주 사용됩니다.
- [[C Sharp]]: 데이터베이스와 상호작용하기 위해 C#에서 SQL을 사용할 수 있습니다.


python: for flat-file database
	CSV: comma-Separated Values

SQL: for relational database
	Creating - create, insert
	Reading - select
	Updating - update
	Deleting - delete, drop

```
.mode csv
.import favorites.csv favorites
.schema

SELECT colums FROM table;
SELECT * FROM favorites; 
```

	AVG
	COUNT
	DISTINCT
	...

```
SELECT CustomerName, City FROM Customers;
```