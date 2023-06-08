# RSS aggregator

## Instructions

```bash
# Install dependencies
go mod tidy
go mod vendor

# Run
go build && ./rssagg
```

## Database

```bash
goose postgres <DB_URL> up
sqlc generate
```
