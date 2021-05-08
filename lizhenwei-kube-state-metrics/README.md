# 官网链接

`
https://github.com/kubernetes/kube-state-metrics/tree/release-1.9/examples/standard
`

这个目录是参考官网的yaml文件，魔改成的helm包。他能收集K8S的每个组件的运行状况，与prometheus搭配使用，注意要安装在kube-monit这个命名空间下

> 如果是K8S集群，则不需要安装这个，因为kubelet里内置了这个

# 安装命令

`
helm install -n kube-monit kube-state-metrics lizhenwei/lizhenwei-kube-state-metrics
`