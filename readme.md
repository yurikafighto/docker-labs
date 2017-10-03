## Docker for beginners

You can also do this tutorial directly on [play with docker training site](http://training.play-with-docker.com/dev-stage1/).

Clean all containers command :
```
docker container rm $(docker container ps -aq)
```

### Stage 1 : The begining

* [1.0 Running your first container](chapters/alpine.md)
* [2.0 Webapps with Docker](chapters/webapps.md)

### Stage 2 : Orchestration

* [3.0 Deploying an app to a Swarm](chapters/votingapp.md)
