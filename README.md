To run the server:

With docker installed type the following command

docker run --name rabbito -p 5672:5672 rabbitmq

docker run --name [nameof the container] -p [localhost to docker container port] : [Port inside docker container] [name of the image to pull]