# helloworldspringbootactuator

## Build docker image 
$ docker build --build-arg JAR_FILE=target/helloworld-0.0.1-SNAPSHOT.jar -t springboot-helloworld:latest .

## Run
$ docker run -p 9000:9000 -t springboot-helloworld:latest