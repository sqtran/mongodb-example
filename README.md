# mongodb-example
Super simple example for connecting to a MongoDB instance and running some queries.

## Containerized MongoDB
```bash
docker run -it --name mangodb -d mongo:4.2
```
## Setup
`mongodb` contains some sample data that can be inserted into the database.

All the code in this repository assumes the database is named `simpsons`.
