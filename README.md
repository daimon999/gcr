# GCR 同步仓库

> 这是一个 Google contaiber registry 镜像同步仓库，目前由 [Travis CI](https://travis-ci.org/mritd/gcrsync) 进行每日自动构建

### 同步信息

仓库每次同步完成后将会追加 [CHANGELOG](changelog)，仓库不保证镜像完全实时同步，如有紧急需求可提交 issue，或发送邮件到 mritd1234@gmail.com

### 用户信息

仓库在 Docker Hub 上用户名为 **`gcrxio`**，所有镜像为 "黑盒" 形式推送，没有创建 Dockerfile 使用 FROM 方式构建是因为不想产生多余镜像层(轻微强迫症)

### 同步工具

同步工具已经开源在 [mritd/gcrsync](https://github.com/mritd/gcrsync)，如想要自行同步可直接使用该工具
