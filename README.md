# elasticsearch statefulset

on nfs server

```
$ mkdir /pkg/elasticsearch-data/esnode-{0..2} -pv
$ chmod 755 /pkg/elasticsearch-data/esnode-{0..2}
```

pull repo

```
$ git clone https://github.com/llmgo/es-sts.git
```

apply all 

```
$ kubectl apply -f .
```

### That's OK !!



