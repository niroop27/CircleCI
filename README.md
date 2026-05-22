# DevOps ABA CI Demo

This repository contains a minimal Java program and CI configuration for GitHub, CircleCI, and Travis CI.

## Run locally

```bash
javac add.java
java add
```

## Files

- add.java: simple Java program that prints the sum of two integers.
- .circleci/config.yml: CircleCI pipeline that compiles and runs the program.
- .travis.yml: Travis CI pipeline that compiles and runs the program.