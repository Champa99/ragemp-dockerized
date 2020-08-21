# Dockerizer RageMP

Docker images that runs the RageMP server on a Debian environment.

Base image: https://hub.docker.com/_/debian

## Summary

The actual game server is running under port 22005 while the http server is under 22006.
Image currently used for testing purposes and still hasn't been tested in production environment. (Will update once it has been tested)

## Running

Run the container with the following command:

`docker run -ti -p 127.0.0.1:22005:22005/tcp -p 127.0.0.1:22005:22005/udp -p 127.0.0.1:22006:22006/tcp -p 127.0.0.1:22006:22006/udp champa99/ragemp`
