# Today I learned

## View LSP logs from COC in nvim

```
:CocList commands
select > workspace.showOutput
```

## Connect observer to iex

```sh
iex --sname k --cookie cookie -S mix
```

then

```sh
erl -sname observer -setcookie cookie -run observer start
```

## Run SQL from file with DB2

```sh
db2 -tvmf filename.sql
```

## Load data from CSV in DB2

```sql
LOAD FROM "/database/config/db2inst1/db_load_temp/smdsear.txt" OF DEL INSERT INTO TMDSEAR
```

## Find what we're compiled against

```sql
SELECT QUALIFIER, BINDTIME
FROM SYSIBM.SYSPACKAGE
WHERE NAME = <PROG_ID>
```
