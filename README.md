# AWX docker-compose

A Docker Compose script with accompanying files to be able to stand up an instance of AWX

How to run:

`git clone https://github.com/lennisthemenace/awx-docker-compose.git`

`cd awx-docker-compose/awx_compose`

`mkdir redis_socket`

`chmod 0777 redis_socket`

You may need to edit the docker-compose.yml to point the mount paths to your full directory path

`sudo docker-compose up`
