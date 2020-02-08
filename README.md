To build the docker machine:
```
cd ./docker
./build.sh
```

Run
```
docker run -it --rm -v $PWD/yocto/output:/home/yoctouser/yocto/output yocto-image:latest
```
