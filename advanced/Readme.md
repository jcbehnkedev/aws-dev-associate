### Install dependencies

```sh
npm install
```

### Start server
```sh
PORT=4567 npm start
```

### Run postgres server
```sh
docker compose up
```

### Install Postgres Client

```sh
sudo apt install postgressql
```

### Create initial database
```sh
createdb study-sync -h localhost -U postgres
```

### Connect to Postgres Client

```sh
psql postgresql://postgres:password@localhost:5432/study-sync
```

## Create a postgres table

## Create Schema

psql study-sync < sql/schema.sql -h localhost -U postgres

## Import Data

psql study-sync < sql/seed.sql -h localhost -U postgres

## Verify Data

sh```
psql postgresql://postgres:password@localhost:5432/study-sync

```sql
SELECT * FROM questions;
```