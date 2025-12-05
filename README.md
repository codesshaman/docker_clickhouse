# docker_clickhouse

Install:

``git clone https://github.com/codesshaman/docker_clickhouse.git``

Create environment file:

``make env``

Change user passwords, storege path and any data:

``nano .env``

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
