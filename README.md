# cork-k8s-scripts

## `kubeadm v1.13.x` bootstrap - external etcd
https://v1-13.docs.kubernetes.io/docs/setup/independent/high-availability/#external-etcd-nodes

## Setup

Copy nodes.sh.example to node.sh and add your inventory

# generate ssh keys

```
ssh-keygen
```

# authorize your key

```
./ssh-copy-id.sh
```

## reset all nodes
```
./0-reset_all.sh
```

## launch haproxy
```
./1-launch_haproxy.sh
```