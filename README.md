## Usage/Examples

First we need to install openapi generator cli

```
npm install @openapitools/openapi-generator-cli -g
openapi-generator-cli version
```

After installing openapi generator cli we can start using it globally&nbsp;

To generate swift client:

```
openapi-generator-cli generate -g swift5 -i https://raw.githubusercontent.com/KeyWeSmart/playground/main/schema.json -o /swift5-client
```

To generate kotlin client:

```
openapi-generator-cli generate -g kotlin -i https://raw.githubusercontent.com/KeyWeSmart/playground/main/schema.json -o /kotlin-client
```
