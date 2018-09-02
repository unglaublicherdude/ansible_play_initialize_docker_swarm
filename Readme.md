# Initialize a docker swarm.

This is a simple way to initialize a docker swarm with ansible. Just install the dependency saved in the requirements.yml.
You just have to provide an inventory file with a group manager and a group worker. When then running the docker-swarm playbook 
against this inventory, a swarm will be initiated on these servers.
