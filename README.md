Very simple example of a Docker container without an OS.  It uses a Go binary that is statically compiled and includes all of its required librarys and resources as the entrypoint.  Because of that there is no OS required in the container.  This makes for a very, very small container (7.4 MB).

Run locally:

```docker run -p 8080:8080 dfinn/no-os-docker-example```

and then point your browser at http://localhost:8080/

[DockerHub Repo](https://hub.docker.com/repository/docker/dfinn/no-os-docker-example)
