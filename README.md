# 项目简洁

## 数据目录的结果如下：

❯ tree .\data\
Folder PATH listing
Volume serial number is C44F-F7C8
C:\USERS\SOURCE\REPOS\OBSERVABILITY\DATA
├─grafana
├─loki
├─prometheus
└─tempo

## `podman compose` 启动命令

```powershell
podman compose up -d  # 启动

podman compose stop   # 停止服务，但是不删除容器

podman compose down   # 删除容器

```

## 在`windows`上建议使用`Docker Desktop`

经过测试发现`podman`在网络的配置上总是会出错，换回`Docker Desktop`反而没有问题，因此建议如果是在`windows`下开发，直接使用`Docker Desktop`
