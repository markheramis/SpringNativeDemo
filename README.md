# Spring Native Demo

This program is a demonstration on the Spring Framework and Spring Native to build Spring based native apps (.exe).

## Pre-requisites
- Download and install [GraalVM 22.3](https://www.graalvm.org/downloads/).
- Add GraalVM 22.3's `bin` path to `Windows Environment Variables` `Path`.
- Add GraalVM 22.3's root directory path to `Windows Environment Variables` as `JAVA_HOME`.
- Download and install [Maven](https://maven.apache.org/download.cgi).
- Add Maven's root directory path to `Windows Environment Variables` `Path`.

## Building Native

Before building the native executable, you first need to install the Developer Command Prompt, you can use the [Using GraalVM and Native Image on Windows 10](https://medium.com/graalvm/using-graalvm-and-native-image-on-windows-10-9954dc071311) as a guide for your setup.

**build the native**

To build the native executable, just run the command below in the `Developer Command Prompt`:

```
mvn clean package -Pnative
```