# K3d

**_k3d is a light weight kubernetes distribution on docker with etcd replaced with sqllite to stand a development cluster. _**

create a single node cluster with defaults

```
k3d cluster create
```

with a name as mycluster with defaults

```
k3d cluster create mycluster

```

create k3s cluster with 1 master and 3 agent nodes

```
k3d cluster create mydemo --servers 1 --agents 3

```
