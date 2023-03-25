## 👋 Welcome to alpine 🚀  

alpine README  
my custom alpinelinux image with bash and tini installed 
  
## Run container

```shell
docker run casjaysdev/alpine bash
```
  
  
## Install my system scripts  

```shell
 sudo bash -c "$(curl -q -LSsf "https://github.com/systemmgr/installer/raw/main/install.sh")"
 sudo systemmgr --config && sudo systemmgr install scripts  
```

## Get source files  

```shell
dockermgr download src alpine
```

OR

```shell
git clone "https://github.com/casjaysdevdocker/alpine" "$HOME/Projects/github/casjaysdevdocker/alpine"
```

## Build container  

```shell
cd "$HOME/Projects/github/casjaysdevdocker/alpine"
buildx 
```

## Authors  

📽 dockermgr: [Github](https://github.com/dockermgr) [Docker](https://hub.docker.com/r/casjaysdevdocker) 📽  
🤖 casjay: [Github](https://github.com/casjay) [Docker](https://hub.docker.com/r/casjay) 🤖  
⛵ CasjaysDevDocker: [Github](https://github.com/casjaysdevdocker) [Docker](https://hub.docker.com/r/casjaysdevdocker) ⛵  
