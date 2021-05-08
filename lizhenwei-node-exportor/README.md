# 参考网站

`
https://www.cnblogs.com/xzkzzz/p/10208115.html
`

这个目录是我参考上面的别人的文档，魔改成的helm包，使用daemonset方式部署。收集宿主机的CPU,内存等资源信息

> 如果是K8S集群，则不需要安装这个，因为kubelet里内置了这个

# 安装命令

`
helm install -n kube-ops node-exportor lizhenwei/lizhenwei-node-exportor
`