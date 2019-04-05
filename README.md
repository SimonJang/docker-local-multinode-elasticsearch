# Run a multinode elasticsearch cluster locally (for testing purposes)

# What?

Running a multinode (3) ElasticSearch cluster locally.

## Instructions

run `docker-compose up` in this folder.

Go to `localhost:9200` for the status of the ElasticSearch cluster
Go to `localhost:9100` for the status of the 3 nodes in the cluster
Go to `localhost:5601` for the Kibana UI

## Why

Running queries on ElasticSearch in an environment simulating a production environment.

# Modifications

Comment out a node or add additional nodes if you want to add/remove existing nodes.
