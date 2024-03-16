# golang-hot-reloading

`golang-hot-reloading` is a working example of cosmtrek [air](https://github.com/cosmtrek/air) for `go` hot reload.

Edit [.air.toml](.air.toml) file for your project. For this example I have to edit some lines to run correctly for this project setup.

## Prerequisite

- Docker-Compose v2

## Run the project

```bash

# run the project
$ docker compose up

```

Now the application should be active. Try to access it.

```bash
$ curl http://localhost:8080/v1/success
```
