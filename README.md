# setup

```
export DATABASE_URL="postgres://localhost/todos"
sqlx db create
sqlx migrate add todos
sqlx migrate run
cargo sqlx prepare
```

# commands

```
cargo run -- add "todo description"
cargo run -- done 1
cargo run -- delete 1
cargo run
```
