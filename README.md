# docker-racket - a Docker container for Racket Scheme

# DOCKER HUB

https://registry.hub.docker.com/u/mcandre/docker-racket/

# EXAMPLE

```
$ make
docker run --rm mcandre/docker-racket:latest racket --version
Welcome to Racket v5.3.6.
```

# REQUIREMENTS

* [Docker](https://www.docker.com/)

## Optional

* [make](http://www.gnu.org/software/make/)
* [Node.js](https://nodejs.org/en/) (for dockerlint)
* [editorconfig-cli](https://github.com/amyboyd/editorconfig-cli) (e.g. `go get github.com/amyboyd/editorconfig-cli`)
* [flcl](https://github.com/mcandre/flcl) (e.g. `go get github.com/mcandre/flcl/...`)
