######################

### pump.io http://pump.io Docker image - listens in port 80

1) Install docker

2) clone  https://github.com/looper25/docker-pump.io

3) go inside folder pump.io

4) configure pump.io.json as per your needs

5) build docker using
docker builder .
    // take care of context, of supervisord and pump.io.json

6)run docker

 docker run -d -p 80:80  <Image Id>
