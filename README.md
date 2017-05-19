# Fluentd Demo

This is the code of the demo from the Fluentd introduction at the first [Cloud Native Computing Meetup](https://www.meetup.com/de-DE/Cloud-Native-Computing-Switzerland/events/238924689/)
in Zurich (11th May, 2017).

1. Follow the recommendations in [Install Elasticsearch with Docker](https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html#docker-cli-run-prod-mode) to run Elasticsearch (check your `vm.max_map_count` settings).
2. run `docker-compose up`
3. Navigate to http://localhost:8080/ to generate some logs.
4. Then navigate to http://localhost:5601/ to open Kibana. You need to apply the default settings the first time.
5. Logs are also stored in Minio once per hour which can be accessed on http://localhost:9000/ with the credentials from the docker-compose.yml: AKIAIOSFODNN7EXAMPLE / wJalrXUtnFEMIK7MDENGbPxRfiCYEXAMPLEKEY

**Credits**: This Docker Compose configuration is derived from [deviantony/docker-elk](https://github.com/deviantony/docker-elk).

# Slides

[Cloud Native Computing - Introduction to Fluentd](https://speakerdeck.com/tobru/cloud-native-computing-introduction-to-fluentd)

