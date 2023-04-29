# Docker-Learning

###  Basic

* How to start a docker container from cmd? <br>
`docker start container_name`

* Run image on bash from cmd. <br>
`docker exec -it container_name bash`

* Create a docker container. <br>
`docker container create -i -t --name mycontainer alpine` <br>
`docker create --name nginx_base -p 80:80 nginx:alpine`

* Inspect all images <br>
`docker ps/docker images -a`

* Docker Run <br>
`docker --run name IMAGE_NAME -e POSTGRES_PASSWORD=**** -d -p port:port DOCKER_IMAGE`

### Database
* to get into postgres <br>
`cd root` <br>
`psql -U user_name`

* to see Databases <br>
`\l`

* to create Database <br>
`create Database();`

* to get into any Database <br>
`\c Database_Name`

* to see tables in Database <br>
`\dt`
