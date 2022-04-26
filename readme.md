# Docker PHP Boilerplate with xDebug

## Startup instructions

```shell
cd docker
cp .env.example .env

// replace UID and USER_NAME with ones from your system
// UID of current user can be found by runnning following commant
id -u 


docker-compose up -d

// System is up and running
```

For better experience edit `hosts` file and add
```shell
127.0.0.1 boilerplate.test:8083
```

Now navigate to http://boilerplate.test:8083/


## Using composer 

```shell
docker-compose run --rm composer install
```



