# cluster-web-example

Repo to test load balancing on a simple application.

----

**NOTE:** You will need to build some executable application to run and drop it into `services/api`

## To run

`docker-compose pull`

`docker-compose up -d` (`-d` starts in background)

### Confirm apps work

`docker ps` will reveal running containers and their ports (assigned to 8080)

You may then run `curl -i localhost:<port-found-in-prev-command>`
