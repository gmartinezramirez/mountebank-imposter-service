# Mountebank Imposter Service

* Dockerized mountebank service with impostor example.
* Mountebank version: 2.2.0.
* NodeJS: 12.1.6 LTS.

## Prequisites

1. Docker.

## Usage

1. To use the impostors in mountebank use the command: docker-compose up

```sh
$ docker-compose up
```
2. You can access mountebank impostors on port 2525. Example: localhost:2525

3. If you want to modify or add impostor you can modify the imposters/imposter.ejs

## Impostor API

* Impostor is available on port 42000.
    * curl localhost:42000/api/centros/
    * In this project is available the postman collection on the folder postman_collections
* URI: /api/centros/
* Method: GET
* Response: 200

```json
{
    "id": "d30cd5da-8424-4922-a7ff-4ecb670a6c0a",
    "nombre": "achs principal"
}
```
