Pentagon in a Kube

All the componentes comunicate pub/sub through the Api-server. 
The Scheduler decide where to run things. 
Control manager delegates processes in each controller: namespace, deployment, replicaSet, pods, services, secrets and ingresess. Also in operators
Proxy takes cares of the routing while the Kubelet makes containers, check liveness and readyness. 
All this over ETCD a Key-Value, Watcher, http interfaces distributed store

[Source](https://vimeo.com/245778144/4d1d597c5e)

[Link]: kubernetes_best_pal_containerd.md

Autor: [Carls Anderson](https://twitter.com/carson_ops?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor)