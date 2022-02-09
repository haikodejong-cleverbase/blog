# Docker compose

useful docker-compose examples

``` yml
version: 3.0

services:
    websocket-server:
        image: nodejs
        volumes:
            ./websocket-server/:/usr/local/src/
```