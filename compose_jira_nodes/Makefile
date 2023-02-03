#For run
podman/docker-compose -f docker-compose-nodes.yml up -d node_1 postgresql
#then, when node_1 started(use for check curl -v http://localhost:8080, and  podman/docker logs node_1) use next command
podman/docker-compose -f docker-compose-nodes.yml up -d node_2 proxy
