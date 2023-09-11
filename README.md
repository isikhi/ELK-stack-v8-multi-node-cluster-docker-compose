# ELK Multi-Cluster Docker Compose Example

This repository contains a Docker Compose file for running Elasticsearch, Logstash, and Kibana (ELK) stack with multi-cluster setup. It is suitable for users who want to process and analyze large log data. Here are the steps to get started:

## Getting Started

To run the project, you'll need Docker and Docker Compose installed. If they are not already installed, you can install them using the following resources:

- [Install Docker](https://docs.docker.com/get-docker/)
- [Install Docker Compose](https://docs.docker.com/compose/install/)

## Running

1. Clone this repository
2. Navigate to the project directory
3. Add this variables to your environment(.env):
  ```
  ELASTIC_STACK_VERSION=8.4.2
  ELASTIC_PASSWORD=yourpassword
  KIBANA_PASSWORD=yourpassword
  APM_PORT=8200
  ES_PORT=9200
  ELASTIC_CLUSTER_NAME=elk-cluster
  ELASTIC_LICENSE=basic
  KIBANA_PORT=5601
  ```

5. Start the ELK stack using Docker Compose
6. Wait until get healthy

