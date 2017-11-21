
# SimGrid platform metamodel

This repository is a small implementation of the [simgrid](simgrid.gforge.inria.fr) platform meta-model. 

Diagram could be used to better understand the concept behind Simgrid. 

more explanation for each concept is available [here](http://simgrid.gforge.inria.fr/simgrid/3.17/doc/platform.html)

Based on SimGrid 3.17

## Diagrams

### Basic concepts

![](https://github.com/barais/simgridmetamodel/blob/master/model/simGridMetaModel.jpg?raw=true)

### Cluster concepts

![](https://github.com/barais/simgridmetamodel/blob/master/model/clusterdiagram.jpg?raw=true)

### Storage concepts

![](https://github.com/barais/simgridmetamodel/blob/master/model/storage.jpg?raw=true)

### Process concepts

![](https://github.com/barais/simgridmetamodel/blob/master/model/ProcessAdActor.jpg?raw=true)

## TODO

- zoneRoute
- link_ctn
- bypassRoute
- bypassASroute
- bypassZoneRoute

## Personal todos

- Better explain the task concepts, and the Java API
- Provide a tutorial for modelling user to create its own plugins based on the energy simulator
- Integrate Disk model in Simgrid based on FAST Experiments
- Create a simple platform for a swarm of lopy gadgets to play with the energy model


## Reference
Built using [sirius editor](http://www.eclipse.org/ecoretools/overview.html)
