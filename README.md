# Vnecoms Devbox Docker

Vnecoms development environment for Magento 2,
based on Docker.

## Installation

```bash
docker-compose up -d //Build in first time and rebuild 
docker ps // All process running
docker-compose stop
docker-compose restart // Restart
```


## What's Included

```
ves-local
├── .gitignore
├── bin
│   └── command build
├── docker-compose.yml
|── env
|   ├── appserver
|   │   └── etc
|   │       └── php.ini
|   └── webserver
|       └── etc
|            └── nginx.conf
└── src (code sources here)
```

Beyond the `docker-compose.yml` file, we have the following:



## Containers

Vnecoms Docker comes with:

* Nginx Alpine
* PHP 7.1 Vnecoms Own image build: Coming soon,
* Mariadb 5.6
* Redis (for cache and session back end)
* RabbitMQ, with a management interface.
* Mailcatcher, for receiving emails.
* RabbitMQ Coming soon
* Varnish for FullPage Cache Coming soon


## Debugging

Xdebug built inside `appserver_debug`

## OS Support

Linux


