# eea.docker.postgres_data

usage: 

create the volume (/usr/share/elasticsearch/data):

    docker run -d --name <app>_elasticsearch_data eeacms/elasticsearch_data

usage with elasticsearch example:

    docker run --restart=always --name <app>_elasticsearch --volumes-from=<app>_elasticsearch_data -d elasticsearch
