# grpc
grpc is clone from https://github.com/grpc/grpc.

The git have executed build:
```cpp
 $ git clone -b $(curl -L http://grpc.io/release) https://github.com/grpc/grpc
 $ cd grpc
 $ git submodule update --init
 $ make
 $ [sudo] make install
```
So we can clone this git, and do some tests.
