# notes-docker-compose

link : link the containers defined in a or different docker-compose.yml fils
depends_on: links, and decide the order of starup, but does't give the guaranty that which one will start first.
when we start the a container all it's  depends_on (not linked) container also gets started( better to use depends_on)


