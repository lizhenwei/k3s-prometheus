# 参考网站

`
https://www.cnblogs.com/xzkzzz/p/10208115.html
`

这个目录是我参考上面的别人的文档，魔改成的helm包，使用deployment方式部署。小心helm delete的时候会删除掉数据哦

> 如果是K8S集群，则不需要安装这个，因为kubelet里内置了这个

# 安装命令

`
helm install -n kube-ops prometheus lizhenwei/lizhenwei-prometheus
`