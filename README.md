# docker_configs

Docker config files for easily creating development, testing or learning environment

# efk_stack

Logging Stack built with Elastic Search, Fluentd and Kibana (EFK) using Docker Compose

## Usage

### For initial run

Since, We are building a customized fluentd image, need to build that image first, this one step command will make sure cluster is up after building the image

```bash
docker-compose up --build
```

### Any runs after initial run

```bash
docker-compose up
```

## References

* [docker compose](https://docs.docker.com/compose/compose-file/)

* [docker compose env files](https://docs.docker.com/compose/env-file/)

* [fluentd docker image](https://hub.docker.com/r/fluent/fluentd/)

* [fluentd entrypoint](https://github.com/fluent/fluentd-docker-image/blob/master/v1.9/alpine/entrypoint.sh)

* [fluentd conf](https://github.com/fluent/fluentd-docker-image/blob/master/v1.9/alpine/fluent.conf)

* [elasticsearch mode](https://www.elastic.co/guide/en/elasticsearch/reference/7.5/docker.html#docker-cli-run-dev-modeS)

* [fluentd elasticsearch conf](https://www.fluentd.org/guides/recipes/elasticsearch-and-s3)

* [fluentd elasticsearch parameters](https://docs.fluentd.org/output/elasticsearch#parameters)

* [configure fluentd](https://docs.fluentd.org/v/0.12/configuration/config-file)

* [fluentd logging](https://docs.docker.com/config/containers/logging/fluentd/)
