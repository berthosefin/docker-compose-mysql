# MYSQL
MySQL environment built using Docker Compose.

## Installation 
* Clone this repository
* Configure .env as needed
* Run docker-compose up -d

```Shell
git clone https://github.com/berthosefin/docker-compose-mysql.git
cd docker-compose-mysql/
cp sample.env .env
// modify .env as needed
docker-compose up -d
docker exec -it CONTAINER_ID mysql -p 
```
