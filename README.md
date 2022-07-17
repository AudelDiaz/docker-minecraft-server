# Docker Minecraft Server
This is a basic implementation of a Docker Minecraft Server.
## Download server.jar
Download latest server.jar file from https://www.minecraft.net/es-es/download/server.
Copy server.jar file in server folder.

## Build image
`docker-compose build --pull`

## Run server
`docker-compose up -d`

## Customize server properties
Inside server folder you are going to find a server.properties file, this is a example, feel free setting up your custom properties.

### Tips and tricks
If you haven't bought Minecraft official game, You should set `online-mode=false` in *server.properties* file in order to use unofficial launchers.

___
*For more content visit https://audeldiaz.work*