Demo: Swarm Clustering
===
TODO - describe application (what it does and what it aims to demonstrate)

Bootstrapping
---
1. Download and install Docker Toolbox
   (https://www.docker.com/docker-toolbox)

2. Follow Get Started tutorial to create a Swarm (https://docs.docker.com/swarm/install-w-machine) and create one Swarm master and two Swarm Agents

3. Confirm your Swarm environment (you should see all nodes here), `docker info`

3. Point your Docker engine to the master, `eval $(docker-machine env --swarm swarm-master)`

4. Go to the directory where you put the `docker-compose.yml` file and run:
  ```
   docker-compose up -d
   docker-compose scale www=4
   ```

5. See the containers running (here you should see them spreading on your nodes, in my case they are created always on the same one), `docker ps`
