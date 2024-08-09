# Docker compose setup for a Dapr statestore based on the CosmosDB Emulator
Because the communication is https I tried to add the self signed certificate of the emulator to the daprd container like described [here](https://docs.dapr.io/operations/configuration/install-certificates/).
Background about the tooling you find [here](docker-cosmosdb/tools.md).
## Run the containers
* Move to docker-cosmosdb dir
* Run docker compose up
