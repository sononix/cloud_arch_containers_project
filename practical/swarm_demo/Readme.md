Demo: Swarm Clustering
===
TODO - describe application (what it does and what it aims to demonstrate)

Bootstrapping
---
1. Download and install Docker Toolbox v1.9.0c (https://github.com/docker/toolbox/releases)

2. Run the install script to provision your machines and discover your Swarm cluster, `chmod +x ./install.sh && ./install.sh`

3. Point your Docker engine to the master, `eval $(docker-machine env --swarm swarm-master)`

4. Install and run the demo app, `docker-compose up -d`
