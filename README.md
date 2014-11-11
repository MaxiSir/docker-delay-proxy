docker-delay-proxy
==================

Docker container for http proxy with static delays.

Run
==================
Bootstrap docker using:
    $(boot2docker shellinit)

run the docker container using:
    docker run -d -p 80:80 --privileged --name proxy -e URL={{your url}} delay-proxy


For more information about docker visit https://www.docker.com/
