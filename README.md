# Multi-module OpenLiberty MicroProfile [![Build Status](https://travis-ci.org/daggerok/openliberty-microprofile.svg?branch=master)](https://travis-ci.org/daggerok/openliberty-microprofile)
Using OpenLiberty MicroProfile Starter built into fat Jars

There are 2 projects generated so that the examples for the Rest Client and/or JWT Auth specification are more realistic in the sense that they actually call an endpoint within another service.

. In the `service-a` directory, you can find an application with the major parts of the application. This can be seen as the 'client'.
. In the `service-b` directory, you can find some endpoints which will be called by code within the client application. This can be seen as the 'backend'.

Have a look in the `readme.md` file in each directory which describes how each project can be built and run.

## Generate

Go to start.microprofile.io site ang choose:

* OpenLiberty MicroProfile 3.0
* Config
* Fault tolerance
* Health check: `/health`
* OpenAPI: `/openapi`, `/openapi/ui`
* Metrics: `/metrics`

## links

* https://www.mvc-spec.org/krazo/docs/install-archetype.html
* https://start.microprofile.io/
* https://www.youtube.com/watch?v=Jemx1BrB45Y
* https://openliberty.io/blog/2018/05/22/microprofile-openapi-intro.html
* JPA: https://openliberty.io/guides/jpa-intro.html#configuring-jpa


