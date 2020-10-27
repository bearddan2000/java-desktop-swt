# java-desktop-swt

## Description
This is a POC project to demonstrate a
java swing application running inside a docker container.

## Tech stack
- docker-cli
- java
  - jre 11
  - swing

## Docker stack
- ubuntu:latest

## To run
```xhost +localhost && sudo ./install.sh -u```

## To stop (optional)
```xhost && sudo ./install.sh -d```
