# Demo LODs

Create a docker of a [demo of Lyon with LODs](https://github.com/VCityTeam/UD-Demo-vcity-lods-lyon).  
_See the [online version](https://lods-lyon.vcityliris.data.alpha.grandlyon.com/)_.

The demo uses a [SimpleServer](https://github.com/VCityTeam/UD-SimpleServer), based on [ExpressJS](https://en.wikipedia.org/wiki/Express.js) web-server.

Clone the repo 

```bash
git clone https://github.com/VCityTeam/UD-Demo-vcity-lods-lyon-docker.git
cd UD-Demo-vcity-lods-lyon-docker
```

Build the docker image with

```bash
docker build -t demo_LODs .
```

and run the container with

```bash
docker run -p 8080:80/tcp -t demo_LODs
```

and open a web browser on URL `http://localhost:8080/`
