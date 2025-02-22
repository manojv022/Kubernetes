
### Dockerfile Instructions
- FROM <image> - base image
- RUN <command> - To add layer on base image / to run command
- COPY <file> <dest> - To Copy file from host machine to Container
- ADD <URL> <dest> - To download file from remote to container
- WORKDIR <path> - To change working dir
- EXPOSE <port> - expose app on container port
- CMD <command> - Run command while container start
- Entrypoint <command> - Run command while container start
- USER <username> - to switch user 
- ARG  - build time variable
- ENV  - env variable 
- SHELL - to change shell (bash, sh, zsh)
- VOLUME

