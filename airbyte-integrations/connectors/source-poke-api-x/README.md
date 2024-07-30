# Poke API
This is a connector for Poke API contributed directly from the Connector Builder

My Poke API connector version X
## Local Development
### Environment Setup
You will need `airbyte-ci` installed. You can find the documentation [here](airbyte-ci).

### Build
This will create a dev image (`source-poke-api-x:dev`) that you can use to test the connector locally.
```bash
airbyte-ci connectors --name=source-poke-api-x build
```

### Test
This will run the acceptance tests for the connector.
```bash
airbyte-ci connectors --name=source-poke-api-x test
```
