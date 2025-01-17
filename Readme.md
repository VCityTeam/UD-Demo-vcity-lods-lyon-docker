# Demo py3dtilers

Create a docker of the [demo of py3dtilers](https://github.com/VCityTeam/UD-Demo-vcity-py3dtilers-lyon).  
_See the [online version]([https://py3dtilers-demo.vcityliris.data.alpha.grandlyon.com/](https://projet.liris.cnrs.fr/vcity/permalink/demo-py3dtilers.html))_.

The demo uses a [SimpleServer](https://github.com/VCityTeam/UD-SimpleServer), based on [ExpressJS](https://en.wikipedia.org/wiki/Express.js) web-server.

Clone the repo

```bash
git clone https://github.com/VCityTeam/UD-Demo-vcity-py3dtilers-lyon-docker.git
cd UD-Demo-vcity-py3dtilers-lyon-docker
```

Build the docker image with

```bash
docker build -t vcity/demo-py3dtilers .
```

and run the container with

```bash
docker run -p 8081:80/tcp -t vcity/demo-py3dtilers
```

and open a web browser on URL `http://localhost:8081/`
