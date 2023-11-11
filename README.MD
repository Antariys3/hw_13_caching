1. Install deps:

```
pip install -r requirements.txt
```

2. Run broker:

```
docker run -p 6379:6379 redis
```

3. Generate blogs into database.

```
python manage.py generate_blogs 50
```

6. Run Django web server.

```
python manage.py runserver
```

