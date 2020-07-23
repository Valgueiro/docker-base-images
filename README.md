# baseDevImages
Dockerfiles used to create the images from [My Docker Hub](https://hub.docker.com/u/valgueiro)

## Install Dev Depencies Bash
It installs dependencies that I use for any development env
For now, what it does:
- Install git

## How to build
It's already **Updated autmoagically by docker push trigger set on the docker hub**, but if you want to do it manually:
- `$ docker build --rm -t <name>:<tag> .`
- `$ docker tag <name>:<tag> <repo path>:<tag for repo>`
- `$ docker push <repo path>:<tag for repo>`