<h1 align="">fintech-devops-exam 👋</h1>
<p>
</p>

> DevOps exam test for a fintech

![Docker-compose](/.github/assets/img/docker-compose-logo.png)

## Table of Contents

* **Docker-compose**
  * [Offical Website](https://www.docker.com/)
  * [Offical Docs](https://docs.docker.com/compose)
  * [Official Github](https://github.com/docker/compose)

## Requirements 
* Docker version 19.03.8;

## Usage

* To use this solution you need to have the docker installed, the solution created was made using docker 19.03.8;
* This stack was create using docker-compose, on the currenty directory there is a docker-compose.yml;
* On the docker-compose.yml it's need to set up BACKEND_HOST variable to the your localhost IP (your machine); 
* Next:

```
docker-compose build 
docker rmi $(docker images -f "dangling=true" -q) 
docker-compose up -d 
``` 

* To test the application you should open your browser at localhost:8080;
* To check the logs:

```
docker logs -f <CONTAINER_ID> 
``` 

Voilá! 

## Author

👤 **Tadeu Bernacchi**

* Website: http://www.tadeubernacchi.com.br/
* Twitter: [@tadeuuuuu](https://twitter.com/tadeuuuuu)
* Github: [@tbernacchi](https://github.com/tbernacchi)
* LinkedIn: [@tadeubernacchi](https://linkedin.com/in/tadeubernacchi)

## Show your support

Give a ⭐️ if this project helped you!

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
