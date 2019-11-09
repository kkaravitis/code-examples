# Example Code Repository

[![Travis CI Status](https://travis-ci.org/thombergs/code-examples.svg?branch=master)](https://travis-ci.org/thombergs/code-examples)

This repo contains example projects which show how to use different (not only) Java technologies.
The examples are usually accompanied by a blog post on [https://reflectoring.io](https://reflectoring.io).

See the READMEs in each subdirectory of this repo for more information.

# Java
All modules require **Java 11** to compile and run.

# Building with Gradle

Modules should be as independent as possible. There are groups of modules that only work together, but other than that, a module should have its own build.

See [build-all.sh](build-all.sh) for all builds that are run in the CI pipeline.

## Building all Modules at Once

In the main folder, run 
```
./gradlew clean build
```

## Building a Module Separately

In the folder of the module, run

```
./gradlew clean build
```

## Non-Java Modules

Some folders contain non-Java projects. For those, refer to the README within the module folder.
