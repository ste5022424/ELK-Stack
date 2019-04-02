FROM docker.elastic.co/elasticsearch/elasticsearch:6.5.4

RUN mkdir -m 777 ./data/elasticsearch
RUN sudo sysctl -w vm.max_map_count=262144