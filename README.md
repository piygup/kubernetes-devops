# kubernetes-devops

Backend application "Sample Spring Boot app" that exposes some HTTP endpoints for CRUD operations and connects to MongoDB on cluster.

**Docker hub URL for docker images**

Spring boot application: https://hub.docker.com/r/piomin/sample-spring-boot-on-kubernetes

Mongo DB: https://hub.docker.com/layers/library/mongo/latest/images/sha256-26ba9dcdb9a225f9d7957e5c5a962af9d9ca403d0c5562e1590338bbae37cd10?context=explore

**URL for Service API tier to view the records from backend tier**

External IP: **35.226.170.60**  PORT: **8080**

1. **GET endpoint for retrive all records** : http://35.226.170.60:8080/persons

2. **GET endpoint for retrive record by Id**: http://35.226.170.60:8080/persons/{id}

3. **POST Endpoint for add record:** http://35.226.170.60:8080/persons

4. **PUT Endpoint for update record:** http://35.226.170.60:8080/persons

5. **DELETE Endpoint by Id:** http://35.226.170.60:8080/persons/665c87841087694507491e56

**Postman colleciton for all above opearation with request body:**

https://api.postman.com/collections/3159356-03ecf368-f140-4ff6-819d-bcfea970b7ff?access_key=PMAT-01HZCW8PFZD5ZMRP322EMWMS5E

**Link for screen recording video showing everything mentioned above**

https://drive.google.com/file/d/1t8k2AcsJkIvWA5RFwPejl9nhG__geRjA/view?usp=drive_link






