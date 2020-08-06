Kubelet best pal, Containerd

Containerd abstracts calls to the kernel in Docker.  Kubelet, as an agent in each node will listen to the api-server and translate the commands, always Pod related, to CRI that will call containerd, if not CRI-O is used, to propagate them to the kernel.

Source:
    [Kubelet](https://kubernetes.io/docs/reference/command-line-tools-reference/kubelet/)
    , [Containerd](https://www.docker.com/blog/what-is-containerd-runtime/)

Author: N/A