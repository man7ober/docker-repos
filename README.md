**Docker:**

<code>docker init</code> - pre-generated docker files <br>
<code>docker compose watch</code> - watch the service/container of an app <br>

**Images:**

<code>docker images</code> - list all images <br>
<code>docker build -t [image_name] .</code> - create an image from dockerfile <br>
<code>docker pull [image_name:tag]</code> - pull an image from docker hub <br>
<code>docker rm [image_id]</code> - remove a local image <br>
<code>docker tag [source_image:tag] [new_image:tag]</code> - tag an image <br>
<code>docker push [image_name:tag]</code> - push an image to docker hub <br>
<code>docker image prune</code> - prune unused images <br>

**Containers:**

<code>docker ps</code> - list all containers <br>
<code>docker run [image_name]</code> - run the container <br>
<code>docker stop [container_id]</code> - stop the container <br>
<code>docker start [container_id]</code> - start the stopped container <br>
<code>docker rm [container_id] -f</code> - remove the container <br>
<code>docker container prune</code> - delete all stopped containers <br>
<code>docker logs [container_id]</code> - view container logs <br>
<code>docker inspect [container_id]</code> - inspect details of a container <br>

**Flags:**

-n - named container
-f - forcefully remove
-a - list all containers
-it - run the container in interactive mode
-p - for exposing port
-v - volumes for store/mount data

**Volumes:**
<code>docker volume ls</code> - list all volumes <br>
<code>docker create volume [volume_name]</code> - create a named volume <br>
<code>docker volume rm [volume_name]</code> - remove a volume <br>
<code>docker volume inspect [volume_name]</code> - inspect details of a volume <br>

**Networks:**
<code>docker network ls</code> - list all networks <br>
<code>docker network inspect [network_name]</code> - inspect details of a network <br>
<code>docker create network [network_name]</code> - create a user-defined bridge network <br>
<code>docker connect network [network_name] [container_name]</code> - connect a container to a network <br>
<code>docker disconnect network [network_name] [container_name]</code> - disconnect a container from a network <br>

**Docker Compose:**

<code>docker compose ps</code> - list containers for specific docker compose project <br>
<code>docker compose up</code> - create and start containers <br>
<code>docker compose down </code>- stop and remove containers <br>
<code>docker compose build</code> - build or rebuild services <br>
<code>docker compose watch</code> - watch services <br>
<code>docker compose logs</code> - view logs for services <br>

**Security:**

<code>docker scout</code> - find vulnerabilities in services <br>
