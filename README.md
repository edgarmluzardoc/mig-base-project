# Base Project

Symfony 5 + NGINX + MySQL 8

## Pre-Requisites

1. Docker
1. Add `127.0.0.1 mig.local` to your `/etc/hosts`

## How to run

1. Clone project and go into its root directory.
1. Build docker image `docker-compose build` (in case you haven't done it already).
1. Run `docker-compose up -d`
1. Go to http://mig.local:8083/ (you should see a Symfony Welcome page)
1. All set!

## Database

These are the default variables for the DB (update them in `code/.env` if needed)

1. DB name: `migdb`
1. User name: `mysqluser`
1. User pass: `mysqlpass`
