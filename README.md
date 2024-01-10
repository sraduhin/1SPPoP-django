# One simple pet project on Python.
### Django part.

## Contains
* django
* postgres
* docker
* nginx

## Setup
```docker network create -d bridge 1SPPoP-network```

## Run
```docker-compose up --build```

run manually to fill database
```
docker exec -it app python3 manage.py populatedb
docker exec -it app python3 manage.py fillcreationdate
```


## Check how does it works

```docker exec -it app python3 manage.pycreatesuperuser```

and visit http://localhost/admin
