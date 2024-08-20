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
psql -U posgres -h 0.0.0.0
psql postgres:password@0.0.0.0:5432
```

