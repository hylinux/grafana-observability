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

## podman compose 下载
https://github.com/docker/compose/releases

docker-compose-windows-x86_64.exe
