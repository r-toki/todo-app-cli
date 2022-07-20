```
export DATABASE_URL="postgres://localhost/todos"
sqlx db create
sqlx migrate add todos
sqlx migrate run
cargo sqlx prepare
```
