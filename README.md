# docker_clickhouse

Install:

``git clone https://github.com/codesshaman/docker_clickhouse.git``

Create environment file:

``make env``

Change passwords and any data:

``nano .env``

Create external network:

``make net``

Build:

``make build``

or

``docker-compose up -d --build``

Down:

``make down``

or

``docker-compose down``

Up:

``make``

or

``docker-compose up -d``
