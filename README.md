# spring-boot-simple-web
This is a simple Spring boot web application. It can generate UUID.

## What you'll need
Java 11

Maven 3.2+

lombok

Docker CE

## To start
To start this application, clone this repo.

Build:

```
mvn install
```

And then run the SpringBootWebApplication class.

## Build Docker image

build image (root directory of project):

```
docker build -f Dockerfile -t docker-spring-boot-web .
```

## Screenshots

#### Home
![screenshot_1](https://user-images.githubusercontent.com/26686429/50365018-848cc100-056a-11e9-9d9a-931b9dc8eb72.png)


#### Generate
![screenshot_2](https://user-images.githubusercontent.com/26686429/50365021-85bdee00-056a-11e9-9c1c-f3cbdb44f393.png)


## About
I started this project for fun which showcase a bit of SpringBoot, JavaScript, Ajax, JSP/HTML, JSTL(EL) and Docker.
