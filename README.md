# Test-r

sudo apt-get update

sudo apt-get install postgresql-client

psql "postgres://tsdbadmin@bgckdiujn1.foy8xm51aw.tsdb.forge.timescale.com:31663/tsdb?sslmode=require"

docker run -d --name timescaledb -p 5432:5432 -e POSTGRES_PASSWORD=password timescale/timescaledb:latest-pg12

