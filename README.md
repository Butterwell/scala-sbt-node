# Scala and sbt Dockerfile

This repository contains **Dockerfile** of [Scala](http://www.scala-lang.org), [sbt](http://www.scala-sbt.org), and [node](http://nodejs.org).

# WIP


## Base Docker Image ##

* [scala-sbt](https://hub.docker.com/hseeberger/scala-sbt)


## Installation ##

1. Install [Docker](https://www.docker.com)
2. Pull [automated build](https://hub.docker.com/r/butterwell/scala-sbt-node/) from public [Docker Hub Registry](https://registry.hub.docker.com):
```
docker pull butterwell/scala-sbt-node
```
Alternatively, you can build an image from Dockerfile:
```
docker build -t butterwell/scala-sbt-node github.com/butterwell/scala-sbt-node
```


## Usage ##

```
docker run -it --rm butterwell/scala-sbt-node
```


## Contribution policy ##

Contributions via GitHub pull requests are gladly accepted from their original author. Along with any pull requests, please state that the contribution is your original work and that you license the work to the project under the project's open source license. Whether or not you state this explicitly, by submitting any copyrighted material via pull request, email, or other means you agree to license the material under the project's open source license and warrant that you have the legal authority to do so.


## License ##

This code is open source software licensed under the [Apache 2.0 License]("http://www.apache.org/licenses/LICENSE-2.0.html").
