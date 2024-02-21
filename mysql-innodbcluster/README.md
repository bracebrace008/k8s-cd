## 说明
拷贝该项目到自己的CD方便管理

## prerequisites
先安装mysql-operator：
``` shell
helm repo add mysql-operator https://mysql.github.io/mysql-operator/
helm repo update
helm install my-mysql-operator mysql-operator/mysql-operator \
   --namespace mysql-operator --create-namespace
```
