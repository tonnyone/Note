## docker swarm 集群限制节点位置

```
node attribute	matches	example
node.id	Node ID	node.id==2ivku8v2gvtg4
node.hostname	Node hostname	node.hostname!=node-2
node.role	Node role	node.role==manager
node.labels	user defined node labels	node.labels.security==high engine.labels	Docker Engine's labels	engine.labels.operatingsystem==ubuntu 14.04
```
