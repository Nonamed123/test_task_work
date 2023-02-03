#For run
podman/docker-compose -f docker-compose-nodes.yml up -d node_1 postgresql haproxy
#then, when node_1 started(use for check -v https://jira01.datacloner.com/, and  podman/docker logs node_1) use next command
podman/docker-compose -f docker-compose-nodes.yml up -d node_2 
podman/docker restart haproxy
