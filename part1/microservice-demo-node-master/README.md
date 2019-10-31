# Microservice demo - node  
This is a "Hello World"-API for the docker/kubernetes-assignment in the course 1dv032 at Linnaeus university.
More information: https://coursepress.lnu.se/kurs/systemadministrationii/examination/

The application is written in [node.js](https://nodejs.org/en/)

The application uses a [redis cache server](https://redis.io/) for handling data.
The connection string to the redis server should be provided through the environment variable
REDIS_URL 


## API
The API have one route at '/'
It will return a json-object with the property "message"

## Example

```
request: http://<url-to-service>
response:
  {message: "Hello from node service, with data from redis :)"}
  ```


