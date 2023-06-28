<br>
<p align="center">
    <a href="https://surrealdb.com#gh-dark-mode-only" target="_blank">
        <img width="300" src="/img/white/logo.svg" alt="SurrealDB Logo">
    </a>
    <p align="center">
    Guide written by Miguel Gargallo
    </p>
    <h1 align="center">
        How to CREATE on SurrealDB
    </h1>
</p>
<br>

Input:

```powershell
	CREATE user:1 SET name='no-reply', email='no-reply@surrealdb.com', age=28
```

Output:

	[
	{
		"result": [
		{
			"age": 28,
			"email": "no-reply@surrealdb.com",
			"id": "user:1",
			"name": "no-reply"
		}
		],
		"status": "OK",
		"time": "673.794µs"
	}
	]

Input:

```powershell
	CREATE item:1 SET name='Item Two', price=20
```

Output:

	[
	{
		"result": [
		{
			"id": "item:1",
			"name": "Item Two",
			"price": 20
		}
		],
		"status": "OK",
		"time": "453.432µs"
	}
	]

