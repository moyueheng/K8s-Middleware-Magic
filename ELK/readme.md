[K8S部署(Elasticsearch+Kibana+Fluentd) - 知乎](https://zhuanlan.zhihu.com/p/428392678)

# 设置需要运行es的节点label

kubectl label nodes salve01 es=log
kubectl label nodes slave02 es=log
kubectl label nodes slave03 es=log
