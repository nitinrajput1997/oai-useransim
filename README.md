# oai-5g-useransim

**Pre-requisite:** 5G core is already running

Build UERANSIM docker image

```
git clone -b docker_support https://github.com/orion-belt/UERANSIM.git
cd UERANSIM
docker build --target ueransim --tag ran:latest -f docker/Dockerfile.ubuntu.18.04 .
```

Run the Ueransim
```
cd oai-cn5g-fed/docker-compose
docker-compose -f docker-compose-ueransim-vpp.yaml up -d
```
