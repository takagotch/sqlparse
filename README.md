### sqlparse
---
https://github.com/andialbrecht/sqlparse

```py
import sqlparse
raw = 'select * from foo; select * from bar;'
statements = sqlparse.split(raw)
statements

first = statements[0]
print(sqlparse.format(first, reindent=True, keyword_case='upper'))

parserd = sqlparse.parse('select * from foo')[0]
parsed.tokens
```

```sh
pip install sqlparse
```

```
```


