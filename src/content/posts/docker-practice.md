---
title: Docker 容器化实践
description: Docker 学习笔记
published: 2026-01-09
tags:
  - 运维部署和云原生
  - 容器化技术
category: 后端开发
---

# Docker 容器化实践

Docker 是一个开源的容器化平台。

## 核心概念

- 镜像 (Image)
- 容器 (Container)
- 仓库 (Registry)

## 常用命令

```bash
docker build -t myapp .
docker run -d -p 80:80 myapp
docker ps
docker logs <container-id>
```
