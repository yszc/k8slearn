# k8slearn

## 常用指令

```

# 操作类
kubectl create namespace feishu  创建命名空间
kubectl apply -f psijob.yaml  -n feishu  应用配置
kubectl delete -f psijob.yaml  -n feishu  删除配置中的资源

# 查看类
kubectl get all -n feishu  查看所有资源
kubectl get configmap -n feishu  查看ConfigMap列表
kubectl describe pod  {pod name} -n feishu  查看Pod详细信息
kubectl describe service  {servic ename} -n feishu  查看Service详细信息
kubectl describe configmap  {config name} -n feishu  查看Pod详细信息

kubectl get pod -n feishu    查看Pod列表
kubectl get pod -n feishu -o wide  显示更多信息
kubectl get pod -n feishu --watch  动态查看状态变更
```
