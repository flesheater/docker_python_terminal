# Docker for running Python 3 terminal apps.

## Create the containers.
```
docker-compose up -d
```

## Install all dependencies
```
docker exec -it tf_python_3 bash /usr/src/app/scripts/install.sh
```

## Run python app.
```
docker exec -it tf_python_3 /usr/local/bin/python3 /usr/src/app/app/app.py
```
