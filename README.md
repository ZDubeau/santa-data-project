# Santa-Data-project

## Requirements

- `python3` + `pipenv` + `pyenv`
- [`docker`](https://docs.docker.com/install/linux/docker-ce/ubuntu/)
- [`docker-compose`](https://docs.docker.com/compose/install/)

## PostgreSQL

Using `docker-compose`, you can manage a local PostgreSQL:

1. Run: `docker-compose up -d`
2. Check: `docker-compose ps`
3. Watch the logs: `docker-compose logs`
4. Stop: `docker-compose down`
5. Remove data: `rm -rf ./data`

By default, you can connect to PostgreSQL with the following URI: `postgresql://santa:claus@localhost:5432/santa_data`.

