# GCR 同步仓库 [![Build Status](https://travis-ci.org/mritd/gcrsync.svg?branch=master)](https://travis-ci.org/mritd/gcrsync)

**注意: 本仓库已停止维护**

**在长达半年的时间里，azure 镜像仓库一直保持高可用状态，其稳定性已经得到足够验证，所以决定暂停本仓库的自动构建并释放免费的 CI 资源；具体详情请参考 [mritd/gcrsync#4](https://github.com/mritd/gcrsync/issues/4)**

> 这是一个 Google contaiber registry 镜像同步仓库，目前由 [Travis CI](https://travis-ci.org/mritd/gcrsync) 进行每日自动构建

### 同步信息

仓库每次同步完成后将会追加 [CHANGELOG](changelog)，仓库不保证镜像完全实时同步，如有紧急需求可提交 issue，或发送邮件到 mritd1234@gmail.com

### 用户信息

仓库在 Docker Hub 上用户名为 **`gcrxio`**，所有镜像为 "黑盒" 形式推送，没有创建 Dockerfile 使用 FROM 方式构建是因为不想产生多余镜像层(轻微强迫症)

### 同步工具

同步工具已经开源在 [mritd/gcrsync](https://github.com/mritd/gcrsync)，如想要自行同步可直接使用该工具

### Azure 同步

目前 azure 已经建立了完整的同步仓库，经过测试其已经同步了大部分 gcr.io 镜像，详情[点击这里](http://mirror.azure.cn/help/gcr-proxy-cache.html)；**如果该仓库长期稳定，本项目可能会考虑停止构建**
