# RecordSelectingNormalizer
This is a connector for RecordSelectingNormalizer contributed directly from the Connector Builder


## Local Development
### Environment Setup
You will need `airbyte-ci` installed. You can find the documentation [here](airbyte-ci).

### Build
This will create a dev image (`🦑-squidward:dev`) that you can use to test the connector locally.
```bash
airbyte-ci connectors --name=🦑-squidward build
```

### Test
This will run the acceptance tests for the connector.
```bash
airbyte-ci connectors --name=🦑-squidward test
```
