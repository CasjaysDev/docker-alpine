## 👋 Welcome to alpine 🚀  

Small. Simple. Secure. Alpine Linux is a security-oriented, lightweight Linux distribution based on musl libc and busybox.  
This image is built with bash, tini, and certbot installed  
  
## Run container

```shell
docker run --name -casjaysdev-alpine casjaysdev/alpine bash
```
  
## Install my system scripts  

```shell
 sudo bash -c "$(curl -q -LSsf "https://github.com/systemmgr/installer/raw/main/install.sh")"
 sudo systemmgr --config && sudo systemmgr install scripts  
```
  
## Get source files  

```shell
dockermgr download src casjaysdev/docker-alpine
```

OR

```shell
git clone "https://github.com/casjaysdev/alpine" "$HOME/Projects/github/casjaysdev/alpine"
```

## Build container  

```shell
cd "$HOME/Projects/github/casjaysdev/alpine"
buildx 
```

## Authors  

🤖 casjay: [Github](https://github.com/casjay) 🤖  
⛵ casjaysdev: [Github](https://github.com/casjaysdev) [Docker](https://hub.docker.com/r/casjaysdev) ⛵  
