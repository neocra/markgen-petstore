# How to create a Pet

This sample demonstrate howto create a pet.

- Authenticate to the pet store platform
- Create the new pet

## Authenticate to the pet store platform

To authenticate request you must to use an oauth authorization.

```rapidoc
spec-url: swagger.yaml
match-paths: POST /pet$
match-type: regex
paths-expanded: true
theme: light
layout: column
schema-style: table
```

## Create the new pet

You can use "POST /pet" to create a new Pet.

```rapidoc
spec-url: https://petstore.swagger.io/v2/swagger.json
match-paths: POST /pet$
match-type: regex
paths-expanded: true
theme: light
layout: column
schema-style: table
```

