[Superset](https://github.com/airbnb/Superset) docker image
=========

[![Build Status](https://travis-ci.org/ssskip/docker-superset.svg?branch=master)](https://travis-ci.org/ssskip/docker-superset)

- docker run --name superset -d -p 8088:8088 ssskip/superset

- init
    * init: 

            docker exec -it superset superset-init

    * init with test data:

             docker exec -it superset superset-demo

- upgrade 

        docker exec -it superset superset-upgrade