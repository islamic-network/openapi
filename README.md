# Islamic Network - OpenAPI

OpenAPI Specifications for Islamic Network APIs (AlAdhan & AlQuran).


## Instructions

Before proceeding, install the following tools:
- [redoc-cli](https://github.com/Redocly/redoc)

To generate the documentation, run the command in the project root: \
```redoc-cli bundle --options.pathInMiddlePanel --output ./public/prayer-times.html ./aladhan-api/openapi.yaml```
