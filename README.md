# Fluentd Demo

This is the code of the demo from the Fluentd introduction at the first [Cloud Native Computing Meetup](https://www.meetup.com/de-DE/Cloud-Native-Computing-Switzerland/events/238924689/)
in Zurich (11th May, 2017).

Just run `docker-compose up` and navigate to port 8080 to generate some logs.
Then navigate to port 5601 to open Kibana. Logs are also stored in Minio from time to time which can be accessed on port 9000.

One important hint: Follow the recommendations in [Install Elasticsearch with Docker](https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html#docker-cli-run-prod-mode) to
run Elasticsearch (f.e. check your `vm.max_map_count` settings).

**Credits**: This Docker Compose configuration is derived from [deviantony/docker-elk](https://github.com/deviantony/docker-elk).

# Slides

[Cloud Native Computing - Introduction to Fluentd](https://speakerdeck.com/tobru/cloud-native-computing-introduction-to-fluentd)

