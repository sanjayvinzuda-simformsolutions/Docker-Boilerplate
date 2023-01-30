# Docker Boilerplate for Rails

![Docker]
![Ruby]
![Rails]
![Postgres]
![Redis]
![Nginx]
![ElasticSearch]
![Kibana]

This boilerplate rails code is created with an intention to facilitate the development of new `Ruby on Rails` projects, without having to install rvm, ruby, postgres, etc, every time.

To run this boilerplate it'll be only necessary to install:

- [Docker](https://docs.docker.com/engine/install/)
- [Docker Compose](https://docs.docker.com/compose/install/)

Boilerplate comes already with a `new app creation` script that basically change this generic name and configure database name as well.

## Getting started

1. Clone the repo
```
git clone <repo_url>
```

2. Enter in the directory
```
cd docker-boiler/
```

3. Inside of directory, create a new app running the command
```
bin/new_app
```

4. It'll move you automatically to your new app, so just run setup configuration
```
bin/setup
```

## Running the project

1. Run docker-compose:
```
docker compose up
```
2. Then access `http://localhost:3000`
