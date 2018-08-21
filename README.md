# grpc-unity-package [![Build Status](https://travis-ci.org/jsmouret/grpc-unity-package.svg?branch=master)](https://travis-ci.org/jsmouret/grpc-unity-package)

gRPC Unity Package


## What is it?

Just a bunch of scripts and a travis config to build a nice package to support gRPC in Unity Engine.

It aims to be as vanilla as possible.

## What's supported at Tag:0.0.7? 

* Grpc.Core version="1.13.1"
* Google.Protobuf version="3.6.0" 
* System.Interactive.Async version="3.1.1"


* Windows / Linux / OSX are extracted straight from the official Nuget package
* Android and iOS are built using Travis

## How to run the example?

* Clone this repository without submodules
* If creating a fresh project, ensure .NET 4.x is enabled
* Download the latest zip from [releases](https://github.com/jsmouret/grpc-unity-package/releases)
* Unzip it in `example/UnityGrpcClient/Assets`
* Open `example/UnityGrpcClient` in Unity
* Run the SampleScene
* Profit!

## Help wanted!

Tests and feedbacks are welcomed. Let's make Unity and gRPC work smoothly together.

## References

* gRPC Team scripts: https://github.com/grpc/grpc/tree/master/src/csharp/experimental
* Where it started: https://github.com/neuecc/MagicOnion
* Where it continued: http://examinedself.com/cross-compile-grpc-unity/
* And further http://chendi.me/2017/07/30/unity-grpc-plugin-en/

### Enjoy!
