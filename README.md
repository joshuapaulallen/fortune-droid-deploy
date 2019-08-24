fortune-droid-deploy
====================

This project describes how to deploy the fortune-droid applications.

* [fortune-droid](https://github.com/joshuapaulallen/fortune-droid)
* [fortune-droid-social](https://github.com/joshuapaulallen/fortune-droid-social)

# Docker

The fortune-droid applications are containerized and can managed with docker-compose.  Running the applications should be as easy as:

```
$ docker-compose -f ${PROJECT_DIR}/docker-compose/docker-compose.yml up
$ curl http://localhost:8080/fortune
```
