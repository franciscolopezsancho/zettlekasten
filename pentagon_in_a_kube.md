Pentagon in a Kube

All the componentes comunicate pub/sub through the Api-server. 
The Scheduler decide where to run things. 
Control manager delegates processes in each controller: namespace, deployment, replicaSet, pods, services, secrets and ingresess. Also in operators
Proxy takes cares of the routing while the Kubelet makes containers, check liveness and readyness. 
All this over ETCD a Key-Value, Watcher, http interfaces distributed store
***Kubelet?? where does it fit?***

[Source](https://vimeo.com/245778144/4d1d597c5e)

Links:  
[Kubelet best pal, containerd](kubelet_best_pal_containerd.md)  
[Blue Green and Red Canaries](blue_green_and_red_canaries.md)
[Repeatable Container](repeatable_container.md)

Autor: [Carls Anderson](authors/carls_anderson.md)
