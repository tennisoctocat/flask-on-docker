# flask-on-docker

This project follows [this tutorial](https://testdriven.io/blog/dockerizing-flask-with-postgres-gunicorn-and-nginx/) to create a web service using Flask, Docker, nginx, and Postgres. 

To run the production environment, use
```
$ docker-compose down -v
$ docker-compose -f docker-compose.prod.yml up -d --build
$ docker-compose -f docker-compose.prod.yml exec web python manage.py create_db
```

This homework is part of [CSCI143 (Big Data)](https://github.com/mikeizbicki/cmc-csci143).
