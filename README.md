# GO_REST_API - Testing with Postman & Newman

### Content
* [postman](#postman)
  * JSON files of exported collection
* [newman](#newman)
  * GUI reports created by newman & htmlextra

Postman
--------------------
#### Files
* Go_REST_API.postman_collection
* Go_REST_API.postman_test_run

Newman
--------------------
#### Files
* Go_REST_API-2022-08-09-11-04-52-131-0

Public Postman Collection
--------------------
* [Go_REST_API_PublicWorkspace](https://www.postman.com/david-cngroup/workspace/public-go-rest-api/collection/22590375-034da0f8-fa9b-429f-adaf-264f7078b0cd?action=share&creator=22590375)

#### Running a Newman
```shell
$ newman run https://www.getpostman.com/collections/e91b265ba709eb1557df -e '.\GO_REST_API Environment.postman_environment.json' -n 2 -r htmlextra
```

Created with ❤️ David Bilnica 2022