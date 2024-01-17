# Business Central E2E Tests with Newman CLI

## Getting started

### Install Newman CLI

`npm install -g newman`

### Run End-to-end tests

`newman run "postman/Business Central API v2.0.postman_collection.json" -e "postman/BusinessCentral.postman_environment.json"`
