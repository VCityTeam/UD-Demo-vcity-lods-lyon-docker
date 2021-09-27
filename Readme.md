# Demo LODs

SimpleServer uses an [ExpressJS](https://en.wikipedia.org/wiki/Express.js) web-server.

Build the docker image with

```bash
docker build -t demo_LODs .
```

and run the container with

```bash
docker run -p 8080:80/tcp -t demo_LODs
```

and open a web browser on URL `http://localhost:8080/`
