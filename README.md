AppBundler Maven Build
======================

This project simply downloads the latest AppBundler code from https://github.com/omegat-org/appbundler which is a fork
of https://github.com/TheInfiniteKind/appbundler, and builds a Maven artifact `org.omegat:appbundler`
with universal native library.

It is built for [OmegaT project](https://github.com/omegat-org/omegat). It may also be useful for 
other java project which want to build Mac .app  arm/intel universal launcher.

To build you will need a macOS machine with Git and Maven 3.6.0+ installed. You can then run:

```bash
$ git clone https://github.com/omegat-org/appbundler-maven-build.git
$ cd appbundler-maven-build
$ mvn clean package
```
