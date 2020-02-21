
![stable](https://img.shields.io/badge/build-stable-green) ![zubair1024](https://img.shields.io/badge/author-zubair1024-cyan)

### Simple HA setup for Node app using Docker Swarm 🐳

##### How to deploy? 

- Initiatize your docker swarm

```bash
$ docker swarm init
```

- To deploy we usse `docker stack` command, but we want to point the stack to our `docker-compose.yml` file

```bash
$ docker stack deploy --compose-file=docker-compose.yml <stack name>
```

- Voila the stack should be deployed and the application can be accessed

## Built With

- [NodeJS](https://nodejs.org/en/)
- [Docker](https://www.docker.com/)

##### Resources:
- https://hub.docker.com/r/dockercloud/haproxy/

## Authors

- **Zubair Ahmed** - [Grizzlybit](https://grizzlybit.info) 👋





