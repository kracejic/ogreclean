Linux
=====

Ogre must be installed

mkdir build
cd build
cmake ..
make
make install
cd dist/bin
./testapplication



Windows - MinGW
===============

Ogre must be installed

mkdir build
cd build
cmake .. -G "MSYS Makefiles" -DOGRE_FRAMEWORK_INCLUDES=c:/ogre/build/sdk/include -DOGRE_FRAMEWORK_PATH=c:/ogre/build/sdk
make install
cd dist/bin
testapplication.exe


