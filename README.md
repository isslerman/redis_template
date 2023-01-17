# redis_template
Redis ready-to-use with docker-compose file and a redis.conf file.
As default server listen to all interfaces. Do not use in production, adjust redis.conf first. 

- using a unique network for all docker to communicate -> docker-dev-network
- you can create the network by usind docker netwrok create docker-dev-network before running. 


start: docker-compose up -d
stop: docker-compose down
