# docker-machine-scripts
Scripts to setup a Docker Swarm demo scenario using docker-machine.

## Inventory

The inventory that contains the list of machines, formed by Docker Swarm Managers and Workers is `.machines`.

Modifying this inventory will affect how many (virtual) machines are generated.

## `machines-*` scripts

The `machines-*` scripts interact with `docker-machine` to create the VM that will form the cluster.


## `swarm-*` scripts

The `swarm-*` scripts interact with the VM cluster to orchestrate the Docker Swarm cluster on top.
