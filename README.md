# sai2-urdfreader
This is a standalone port of the ROS urdf reader for use with the SAI2 libraries.

## Dependencies
It depends on tinyxml2. 
On Ubuntu :
```
sudo apt-get install libtinyxml2-dev
```
On MAC :
```
brew install tinyxml2
```

## Build instructions 
from the base directory
```
mkdir build
cd build
cmake .. && make -j8
