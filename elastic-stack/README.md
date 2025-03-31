# Elasticsearch and Kibana Stack

This directory contains the Docker Compose configuration for running Elasticsearch and Kibana.

## Default Credentials

- Username: elastic
- Password: changeme

## Ports

- Elasticsearch: 9200, 9300
- Kibana: 5601

## Volumes

Data is stored in:
- `/docker_data/elastic-stack/elasticsearch/data` - Elasticsearch data
- `/docker_data/elastic-stack/elasticsearch/config` - Elasticsearch configuration
- `/docker_data/elastic-stack/kibana` - Kibana data

## Network

Uses the `shared_bridge_1` external network. 