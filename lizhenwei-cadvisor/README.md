# 官网链接

`
https://github.com/google/cadvisor/tree/master/deploy/kubernetes
`

这个目录是我用kustomize 生成yaml文件，魔改成的helm包，使用daemonset方式部署。这样在K3S的每一个机器上都会生成一个cAdvisor采集CPU,内存等信息。

> 如果是K8S集群，则不需要安装这个，因为kubelet里内置了这个

# 安装命令

`
helm install -n kube-ops cadvisor lizhenwei/lizhenwei-cadvisor
`