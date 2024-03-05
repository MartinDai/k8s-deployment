# k8s-deployment

k8s笔记，记录部署k8s应用需要的配置文件

## 创建namespace

```shell
kubectl create -f wechat-robot-namespace.yaml
```

## 部署应用

```shell
kubectl create -f wechat-robot-deployment.yaml
```

## 创建服务

```shell
kubectl create -f wechat-robot-service.yaml
```