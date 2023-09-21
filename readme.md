# 思源笔记 免登录同步

Docker 镜像见 [Packages](https://github.com/zerolfx/siyuan-pro/pkgs/container/siyuan-pro)，桌面端应用见 [Releases](https://github.com/zerolfx/siyuan-pro/releases)。

如果你想自行构建，可以参考下面的步骤：

1. Fork 本仓库
2. （可选）根据需要修改 patch 文件。
3. 手动触发 Github Actions，输入想要构建的 tag，如 `v2.10.6`。 

Q: 为什么要构建免登录版本？

A: 思源笔记的优秀之处不在此赘述，我也愿意并已经为其本地额外功能（通过 S3/WebDAV 同步）付费。但是需要使用国内手机号绑定的账号登录来验证付费有些难以接受。 

部分相关讨论（其实社区里还有很多讨论）：https://github.com/siyuan-note/siyuan/issues/8835

Q: 和类似项目的区别是什么？比如：
- https://github.com/siyuan-community/siyuan
- https://github.com/EightDoor/siyuan
- https://github.com/hac425xxx/siyuan

A: 本项目的特点：
- 提供了 patch 和 CI，用户可以自行构建并保证没有预期外的修改。
- 除了二进制包外，还提供了 Docker 镜像供私有化部署。