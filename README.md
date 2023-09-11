# Today I learned

## View LSP logs from COC in nvim

```
:CocList commands
select > workspace.showOutput
```

## Connect observer to iex

```
iex --sname k --cookie cookie -S mix
```

then

```
erl -sname observer -setcookie cookie -run observer start
```
