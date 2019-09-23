# K8S-happy-IP

K8s-happy-IP is a kubernetes operator that manages virtual interfaces on Kubernetes nodes to be used
by node-local services, such as DNS node-cache, dd-agent, dd-zipkin-proxy, kube2iam, kiam...

It is inspired by [kube-magic-ip-address](https://github.com/mumoshu/kube-magic-ip-address), but
implemented as a Kubernetes operator written in Golang using [Kubebuilder}(https://github.com/kubernetes-sigs/kubebuilder).
