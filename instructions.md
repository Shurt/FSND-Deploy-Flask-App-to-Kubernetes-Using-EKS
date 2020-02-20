* docker image build -t jwt-api-test:1.0 jwt-api-test/
* docker container run --publish 80:8080 --name jwt-api-test jwt-api-test:1.0