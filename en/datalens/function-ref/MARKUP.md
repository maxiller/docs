---
editable: false
sourcePath: en/_api-ref/datalens/function-ref/MARKUP.md
---

# MARKUP



#### Syntax {#syntax}


```
MARKUP( arg_1, arg_2, arg_3 [ , ... ] )
```

#### Description {#description}
Merges marked up text pieces. Can also be used for converting strings to marked up text.

**Argument types:**
- `arg_1` — `Markup | String`
- `arg_2` — `Markup | String`
- `arg_3` — `Markup | String`


**Return type**: `Markup`

#### Example {#examples}

```
MARKUP(BOLD([a]), ': ', [b])
```


#### Data source support {#data-source-support}

`ClickHouse 21.8`, `Files`, `Google Sheets`, `Microsoft SQL Server 2017 (14.0)`, `MySQL 5.7`, `Oracle Database 12c (12.1)`, `PostgreSQL 9.3`, `Yandex Documents`, `YDB`.
