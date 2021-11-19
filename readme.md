## eksの基本

```shell
eksctl create cluster
```

カスタマイズする場合は
```shell
eksctl create cluster -f cluster.yaml
```


削除する場合は

```shell
eksctl delete cluster -f cluster.yaml
```