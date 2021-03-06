# docker-swift

![swift](https://raw.githubusercontent.com/hamin/EventSource.Swift/master/swift-logo.png)

[![Run Status](https://api.shippable.com/projects/58663bf6f6c7101000c4038f/badge?branch=master)](https://app.shippable.com/github/swiftdocker/docker-swift)

### An Ubuntu 16.04 Docker image for [Swift](https://swift.org).

#### You can find the Docker Hub repo here: [https://hub.docker.com/_/swift/](https://hub.docker.com/_/swift/)


### Docker Instructions

##### Pull the Docker Image From Docker Hub:

```bash
docker pull swiftdocker/swift
```

##### Create a Container from the Image and Attach It:

```bash
docker run --privileged -i -t --name swiftfun swiftdocker/swift:latest /bin/bash
```

##### To Start and Attach Your Image Later:

Start your image with name `swiftfun`

```bash
docker start swiftfun
```

and then attach it

```bash
docker attach swiftfun
```


## Contributions

Contributions via pull requests are welcome and encouraged :)

## License

docker-swift is licensed under the [Apache License, Version 2.0](LICENSE.md).
