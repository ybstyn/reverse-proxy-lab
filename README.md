# 反向代理代码与交付

本仓库存放软件交付入口、配置示例和使用说明。完整客户端、可编辑代码、逆向参考、原生库及文档随 Release 附件提供。

## SWZS Debian ARM64 0.4.0

[打开版本下载页](https://github.com/ybstyn/reverse-proxy-lab/releases/tag/v0.4.0)

| 文件 | 下载 |
| --- | --- |
| 完整 ZIP（451,495,053 字节） | [SWZS-Debian-ARM64-0.4.0.zip](https://github.com/ybstyn/reverse-proxy-lab/releases/download/v0.4.0/SWZS-Debian-ARM64-0.4.0.zip) |
| Linux tar.gz（444,987,884 字节） | [SWZS-Debian-ARM64-0.4.0.tar.gz](https://github.com/ybstyn/reverse-proxy-lab/releases/download/v0.4.0/SWZS-Debian-ARM64-0.4.0.tar.gz) |
| 原始使用与代码说明 | [README.md](https://github.com/ybstyn/reverse-proxy-lab/releases/download/v0.4.0/README.md) |
| 原始 SHA256 校验文件 | [SWZS-Debian-ARM64-0.4.0.SHA256SUMS](https://github.com/ybstyn/reverse-proxy-lab/releases/download/v0.4.0/SWZS-Debian-ARM64-0.4.0.SHA256SUMS) |

ZIP 和 tar.gz 是同一交付的两种打包形式，任选其一，完整解压后阅读包内 README 和 docs。GitHub 自动生成的 “Source code” 压缩包只包含本仓库文件，不包含上述完整交付。

目标环境为 Debian Linux ARM64（aarch64），不是 Debian 安装镜像。包内包含按提供者要求预置的明文 PIN、Wi-Fi 等参数，本版本按用户明确授权原样公开。

原包说明的已完成范围为 CPE 核心激活、登录、心跳和注销；不代表原厂全部 GUI、组件或完整可编译 C++ 工程均已恢复。具体依赖、真实 Wi-Fi 接口要求、部署方式、证据和未完成范围，以交付包内文档为准。本次发布核对文件完整性，不重新运行激活或联系业务服务器。

## 仓库目录

- `src/`：后续独立维护的代码。
- [docs/](docs/README.md)：交付说明入口。
- [configs/](configs/README.md)：后续配置示例和模板。
