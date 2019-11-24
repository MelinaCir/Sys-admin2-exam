# Microservice demo - Go  
This is a "Hello World"-API for the docker/kubernetes-assignment in the course 1dv032 at Linnaeus university.

More information: https://coursepress.lnu.se/kurs/systemadministrationii/examination/

The application is written in [go](https://golang.org/)

## API
The API have one route at '/'
It will return a json-object with the property "message"

## Example

```
request: http://<url-to-service>
response:
  {message: "Hello from GO!"}
  ```


