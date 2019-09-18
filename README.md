# bullet-train-aio

[Bullet Train](https://bullet-train.io/) All In One Project. This is a docker-compose project to boot https://github.com/SolidStateGroup/bullet-train-frontend and https://github.com/SolidStateGroup/bullet-train-api alongside a PostgreSQL database.

You should only use this for testing / development and to try out Bullet Train. The setup is not production ready! 

## To get it setup

```bash
git clone git@github.com:SolidStateGroup/bullet-train-aio.git
git submodule update --init --recursive
docker-compose up
```

You can set up the Django Admin user by visiting ```http://localhost:8000/api/v1/users/init/```. This will create an admin user with the username ```admin@example.com``` and password ```password```.

Then browse to [https://localhost:8080](https://localhost:8080).
