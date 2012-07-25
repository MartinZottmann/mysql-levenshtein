# Levenshtein for MySQL

This is an implementation of Levenshtein distance calculation in MySQL.

#### Installation

```
$ mysql database-name < levenshtein.sql
```

#### Usage

```sql
SELECT levenshtein("Levenshtein", "Levenstein");

Result: 1
```

```sql
SELECT levenshtein_ratio("levenshtein", "Levenstein");

Result: 91
```