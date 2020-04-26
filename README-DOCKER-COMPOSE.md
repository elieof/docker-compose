# JHipster generated Docker-Compose configuration

## Usage

Launch all your infrastructure by running: `docker-compose up -d`.

## Configured Docker services

### Service registry and configuration server:

- [JHipster Registry](http://localhost:8761)

### Applications and dependencies:

- eo2Gateway (gateway application)
- eo2Gateway's mysql database
- eo2Gateway's elasticsearch search engine
- eo2Uaa (uaa application)
- eo2Uaa's mysql database
- eo2Uaa's elasticsearch search engine
- eooQuiz (microservice application)
- eooQuiz's mongodb database
- quotes (microservice application)
- quotes's postgresql database

### Additional Services:

- Kafka
- Zookeeper
- [JHipster Console](http://localhost:5601)
- [Zipkin](http://localhost:9411)
