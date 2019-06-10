p::3rd, a c++ package manage tool
============

used to manage third-party open source package, user-local build and install package automatically.

![c++11](https://img.shields.io/badge/c++11-only-green.svg)
![amd64](https://img.shields.io/badge/x86--64-only-green.svg)
![linux](https://img.shields.io/badge/linux-only-green.svg)

Requirements
------------

- bash
- make
- cmake
- gcc && g++

 
Support Packages
------------

- gtest
- gflags
- protobuf3
- protobuf
- zlib
- isa-l
- libunwind
- rapidjson
- cryptopp
- flatbuffers

How To Use
------------

```
# only install protobuf3
./build.3rd protobuf3

# only install zlib
./build.3rd zlib

# this command will install default package list
# (gtest + gflags + protobuf3 + gperf + libunwind)
./build.3rd
```
