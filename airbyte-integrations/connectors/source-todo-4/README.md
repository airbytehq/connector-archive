# SOURCE TODOThis is a connector for SOURCE TODO contributed directly from the Connector Builder

HI MOM 8
## Local Development
### Environment Setup
You will need `airbyte-ci` installed. You can find the documentation [here](airbyte-ci).

### Build
This will create a dev image (`source-todo-4:dev`) that you can use to test the connector locally.
```bash
airbyte-ci connectors --name=source-todo-4 build
```

### Test
This will run the acceptance tests for the connector.
```bash
airbyte-ci connectors --name=source-todo-4 test
```