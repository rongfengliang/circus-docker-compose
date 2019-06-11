# running circus with separate docker image

## how to running

* start

```code
docker-compose up -d
```

* view web console

```code
open http://localhost:8080
```

* web console zeromq config

```code
connect address set tcp://circus:5555
```