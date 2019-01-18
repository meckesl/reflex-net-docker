builds the image

- docker build .

lists all built images

- docker images

lists all processes (running containers)

- docker ps

run the image

- docker run 'imageId'

get the ip address

- docker inspect 'containerNameOrId' | grep '"IPAddress"' | head -n 1

exec inside container (console uses sh or bash)

- docker exec -it 'containerNameOrId' sh
