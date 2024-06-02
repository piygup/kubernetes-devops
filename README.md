# kubernetes-devops

Backend application "simple Spring Boot app" that exposes some HTTP endpoints for CRUD operations and connects to MongoDB on cluster.

**Docker hub URL for docker images**

Spring boot application: https://hub.docker.com/r/piomin/sample-spring-boot-on-kubernetes

Mongo DB: https://hub.docker.com/layers/library/mongo/latest/images/sha256-26ba9dcdb9a225f9d7957e5c5a962af9d9ca403d0c5562e1590338bbae37cd10?context=explore

**URL for Service API tier to view the records from backend tier**

External IP & Port: **35.226.170.60:8080**

1. **GET endpoint for retrive all records** : http://35.226.170.60:8080/persons

2. **GET endpoint for retrive record by Id**: http://35.226.170.60:8080/persons/{id}

3. **POST Endpoint for add record:** http://35.226.170.60:8080/persons

4. **PUT Endpoint for update record:** http://35.226.170.60:8080/persons

5. **DELETE Endpoint by Id:** http://35.226.170.60:8080/persons/665c87841087694507491e56







