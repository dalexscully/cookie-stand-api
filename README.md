# LAB - Class 34

## Project: cookie-stand-api

## Author: Domaine Scully

# Cookie Stand

This app includes a frontend site that displays data about cookie stands. It also supports a Django REST Api. It uses a PostgreSQL database supplied by ElephantSQL.

## Links and Resources

[ElephantSQL](https://api.elephantsql.com/console/85760e34-8351-4df0-8088-8c1ba03f1eb6/browser?#)

## Setup

* Requires a .env

## Test and How to initalize

`docker compose up`

`docker compose run web python3 manage.py test`

## Run

docker compose up

Frontend: http://0.0.0.0:8000/

Backend: http://0.0.0.0:8000/api/v1/cookie_stand/

Admin: http://0.0.0.0:8000/admin/
