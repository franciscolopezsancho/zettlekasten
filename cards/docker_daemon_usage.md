The docker daemon.sock is a file that allows a process to communicate with the docker server. 
This communication can be through `unix`, `tcp` or `fd` sockets. When both, client and server, are in local `unix` can be used, when the communication is remote `tcp` must be enabled (in macOS ~/.docker/daemon.json). Bear in mind the client doesn't have to be `docker` can very well be `curl` using a unix socket. You can try `curl --unix-socket /var/run/docker.sock http://localhost/images/json | jq` to get all the images, for instance.

[](kubelet_best_pal_containerd.md)