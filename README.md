# One simple pet project on Python.
### Django part.

## Contains
* django
* postgres
* docker
* nginx


run
```docker-compose up --build```


setup
```
docker exec -it app python3 manage.py populatedb
docker exec -it app python3 manage.py fillcreationdate
```


check how does it works

```docker exec -it app python3 manage.pycreatesuperuser```

and visit http://localhost/admin
