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
* Go_REST_API-2022-08-09-12-31-23-111-0

Public Postman Collection
--------------------
* [Go_REST_API_PublicWorkspace](https://www.postman.com/david-cngroup/workspace/public-go-rest-api/collection/22590375-0527e5cc-461c-4f03-aa22-51a41236790d?action=share&creator=22590375)

#### Running a Newman
```shell
$ newman run https://www.getpostman.com/collections/30133ce98048dcf5c73d -e '.\GO_REST_API Environment.postman_environment.json' -n 2 -r htmlextra
```

Created with ❤️ David Bilnica 2022