# ci-docker-in-docker
Docker image to help to understando how to configure a Docker inside a Docker but launching containers as siblings

To run container

``
docker run -v /var/run/docker.sock:/var/run/docker.sock -it gtunon/docker-in-docker
``
