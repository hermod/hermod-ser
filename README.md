Introduction
=============

The purpose of this hermod-[java|csharp|cpp]-ser-* projects is to define a high level framework to serialize messages based on key/value (key is an int) to build very fast messaging applications.

Goals/Drivers
=============

You can make an analogy with logger and SLF4J for example for the serialization.

Our 3 drivers are:

* Performance
* Interoperability (for both: implementation and/or language)
* Low coupling between components. 

The API 
* hermod
** hermod-java-ser-api
** hermod-csharp-ser-api (TODO)
** hermod-cpp-ser-api (TODO)

The implementations are
* hermod
** hermod-java-ser-hermod
** hermod-csharp-ser-hermod (TODO)
** hermod-cpp-ser-hermod (TODO)
* googleprotocolbuffer (TODO)
** hermod-java-ser-gpb (TODO)
** hermod-csharp-ser-gpb (TODO)
** hermod-cpp-ser-gpb (TODO)
* others ?

Links
=====

[![Build Status](https://buildhive.cloudbees.com/job/hermod/job/hermod-java-parent/badge/icon)](https://buildhive.cloudbees.com/job/hermod/job/hermod-java-parent/)


The [maven site Link](https://buildhive.cloudbees.com/job/hermod/job/hermod-java-parent/site/).
