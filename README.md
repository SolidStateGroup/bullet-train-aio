# bullet-train-aio

Bullet Train All In One Project

docker-compose project to boot https://github.com/SolidStateGroup/bullet-train-frontend and https://github.com/SolidStateGroup/bullet-train-api alongside a PostgreSQL database.

You should only use this for testing / development and to try out Bullet Train.

## To get it setup

```bash
git clone git@github.com:SolidStateGroup/bullet-train-aio.git
git submodule update --init --recursive
docker-compose up
```

The browse to https://localhost:8080