<br>
<p align="center">
    <a href="https://surrealdb.com#gh-dark-mode-only" target="_blank">
        <img width="300" src="/img/white/logo.svg" alt="SurrealDB Logo">
    </a>
    <p align="center">
    Guide written by Miguel Gargallo
    </p>
    <h1 align="center">
        How to RELATE on SurrealDB
    </h1>
</p>
<br>

Input:

```powershell
	RELATE user:1->bought->item:1 SET price=20, created_at = time::now()
```

Output:

	[
	{
		"result": [
		{
			"created_at": "2022-10-01T16:16:01.350849157Z",
			"id": "bought:rqu54w8dmc96u4a266zs",
			"in": "user:1",
			"out": "item:1",
			"price": 20
		}
		],
		"status": "OK",
		"time": "365.719µs"
	}
	]

