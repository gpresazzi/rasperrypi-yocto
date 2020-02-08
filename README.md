##Yocto in a docker machine

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

Build the image, inside docker terminal
```
#> export TEMPLATECONF=~/yocto/source/meta-pisensor/custom/
#> source source/poky/oe-init-build-env build
#> bitbake pisensor-image 
```
