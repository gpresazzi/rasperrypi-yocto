To build the docker machine:
```
cd ./docker
./build.sh
cd ..
```

Run docker
```
docker run -it --rm -v $PWD/yocto:/home/yoctouser/yocto yocto-image:latest
```

Build the image
```
#> source source/poky/oe-init-build-env build
#> bitbake pisensor-image 
```
