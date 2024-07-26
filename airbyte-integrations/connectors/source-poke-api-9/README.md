# PokeThis is a connector for Poke contributed directly from the Connector Builder


## Local Development
### Environment Setup
You will need `airbyte-ci` installed. You can find the documentation [here](airbyte-ci).

### Build
This will create a dev image (`source-poke-api-9:dev`) that you can use to test the connector locally.
```bash
airbyte-ci connectors --name=source-poke-api-9 build
```

### Test
This will run the acceptance tests for the connector.
```bash
airbyte-ci connectors --name=source-poke-api-9 test
```
