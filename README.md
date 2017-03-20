# k8s


## Installation
- Install Vagrant - https://www.vagrantup.com/downloads.html
- Install Virtual Box - https://www.virtualbox.org/wiki/Downloads

## Bringing up the cluster
The below will by default bring up one master node and one worker node.
The number of worker nodes can be configured in config.rb

```
    git clone https://github.com/vvb/k8s
    cd k8s
    vagrant up
```

## Teardown the cluster

```
    vagrant destroy -f
```

