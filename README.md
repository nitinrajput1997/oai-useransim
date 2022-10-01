# oai-5g-useransim

Build UERANSIM docker image

```
git clone -b docker_support https://github.com/orion-belt/UERANSIM.git
cd UERANSIM
docker build --target ueransim --tag ran:latest -f docker/Dockerfile.ubuntu.18.04 .
```
