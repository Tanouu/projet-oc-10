# BobApp

Clone project:

> git clone XXXXX

## Front-end 

Go inside folder the front folder:

> cd front

Install dependencies:

> npm install

Launch Front-end:

> npm run start;

### Docker

Pull the latest front image:

> docker pull tanouu/bobapp-front

Start the container:

> docker run -d -p 4200:80 tanouu/bobapp-front

## Back-end

Go inside folder the back folder:

> cd back

Install dependencies:

> mvn clean install

Launch Back-end:

>  mvn spring-boot:run

Launch the tests:

> mvn clean install

### Docker

Pull the latest back image:

> docker pull tanouu/bobapp-back

Start the container:

> docker run -d -p 8080:8080 tanouu/bobapp-back

The frontend will be available at:
http://localhost:4200

The backend API is available at:
http://localhost:8080/api/joke

Sonar analysis is available at:

https://sonarcloud.io/summary/overall?id=Tanouu_projet-oc-10&branch=main

Docker Hub:

https://hub.docker.com/u/tanouu