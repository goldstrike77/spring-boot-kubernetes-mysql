# Spring Boot Kubernetes and MySQL

Sample project to test and deploy spring boot application with mysql database in kubernetes.

## Prerequisite

- Docker with kubernetes enabled
- Kubernetes command-line tool(kubectl)
- JDK 21 LTS
- Gradle 8

- Test application :

```curl
curl -X GET \
  http://localhost:31371/api/v1/pets \
  -H 'Accept: application/json' \
  -H 'Content-Type: application/json'
  
```

Response should be :

```json
[
  {
    "name": "Puffball",
    "owner": "Diane",
    "species": "hamster",
    "sex": "f",
    "birth": "1999-03-30",
    "death": null
  }
]
```