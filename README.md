# Docker Images for Jenkins development
🚢[Docker Image](https://hub.docker.com/r/jenkins/jenkins/)

## Installation

1. Install [docker](https://docs.docker.com/engine/installation/) and [docker-compose](https://docs.docker.com/compose/install/) ;

2. Copy `docker-compose.yml` file to your project root path, and edit it according to your needs ;

3. From your project directory, start up your application by running:

```sh
docker-compose up -d
```

4. View the generated administrator password to log in the first time.
```sh
docker exec my-jenkins-1 cat /var/jenkins_home/secrets/initialAdminPassword
```

5. If you want, down application:

```sh
docker-compose down
```

## Licence

This work is under [MIT](LICENCE) licence.