# docker-node-xvfb
Node.js + Xvfb (+ Google Chrome) so you can quickly dockerize virtual-browser-based apps!

Head over to the [Docker Hub Repo](https://hub.docker.com/r/itsjustcon/node-xvfb) for more info.

### Build:
```
docker build --tag=itsjustcon/node-xvfb .
```

### Deploy:
*Be careful with this!* Docker Hub is configured for Automated Builds - meaning
this container image will be automatically re-built & updated on git push.
```
docker push itsjustcon/node-xvfb
```
