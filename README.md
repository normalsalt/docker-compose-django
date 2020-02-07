# Django

https://www.djangoproject.com/

## docs

https://docs.djangoproject.com/en/3.0/

## up

```
docker-compose up -d
```

Now, open http://localhost:8000 in your browser.

## migrate

```
docker-compose run --rm web python manage.py migrate
```

## createsuperuser

```
docker-compose run --rm web python manage.py createsuperuser
```
