# MeterSphere Helm Chart 部署

## 使用示例
1. 下载helm chart包，放置kuberneter环境；
2. 解压helm chart包，修改values.yaml文件，对镜像版本和存储类按实际使用环境进项修改；
```bash
tar -zxvf dataease-xxx.tgz
vi dataease/values.yaml
```
3. 安装
```bash
helm install dataease dataease-xxx.tgz -f dataease/values.yaml
```
