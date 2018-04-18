Elky Docker
=========================

Tis project is a sample docker-compose facilitated docker setup for some common ELK (elasticsearch logstash kibana) components.

Status
-------------------------

Currently has the following setup
* Elasticsearch
* Logstash
* Rabbitmq

There is a global docker-compose.yml that will start all components together.  Each component has a docker-compose.yml for itself that can be started individually.  It is missing any sort of linking when started in standalone mode at the momemnt and will need hosts / ports change accordingly. 
