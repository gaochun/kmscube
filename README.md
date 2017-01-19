# kmscube
## Get source code with git
```
git clone https://github.com/gaochun/kmscube.git
git submodule update --init --recursive
```

## Build steps
```
cd third_party/json-c
./autogen.sh
./configure
make
cd ../..
./autogen.sh
./configure
make
```
