[Caravel](https://github.com/airbnb/caravel) docker image
=========

[![Build Status](https://travis-ci.org/ssskip/docker-caravel.svg?branch=master)](https://travis-ci.org/ssskip/docker-caravel)

- docker run --name caravel -d -p 8088:8088 ssskip/caravel

- init
    * init: 

            docker exec -it caravel caravel-init

    * init with test data:

             docker exec -it caravel caravel-demo

- upgrade 

        docker exec -it caravel caravel-upgrade