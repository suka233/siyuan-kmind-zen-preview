# KMind Zen for SiYuan — Preview builds

[中文](#中文) · [English](#english)

---

## 中文

这个仓库只提供 **KMind Zen 思源插件** 的预览测试包，**不含源代码**。正式版请在思源集市安装（发布仓库：[suka233/siyuan-kmind-zen](https://github.com/suka233/siyuan-kmind-zen)）。

### 下载

最新预览包：<https://github.com/suka233/siyuan-kmind-zen-preview/releases/download/preview/package.zip>

仓库里始终只保留最新的一个包。构建时间、校验值（SHA-256）见 [Release 说明](https://github.com/suka233/siyuan-kmind-zen-preview/releases/tag/preview)。

### 安装

要求思源 3.1.0 及以上。

1. 下载 `package.zip` 并解压。
2. 打开思源工作空间下的 `data/plugins/` 目录。
3. 新建（已存在则先清空）文件夹 `siyuan-kmind-zen`，把解压出的**全部文件**放进去，`plugin.json` 要直接在这个文件夹里。
4. 重启思源。

如果你已经从集市装了正式版，预览包会覆盖它。想回到正式版，在集市里重新安装即可。

### 注意

- 预览包的版本号可能与集市上的正式版相同，但内容更新。
- 预览包包含尚未正式发布的新功能和新的数据格式。用预览包保存过的导图，**可能无法在正式版或更早的版本中正常打开或编辑**。请不要在重要数据上使用，使用前先备份工作空间。
- 与正式版一样，预览包会连接 `kmind.app` 的服务。

---

## English

This repository only hosts **preview builds of the KMind Zen SiYuan plugin**. It contains **no source code**. For the stable version, install it from the SiYuan marketplace (release repository: [suka233/siyuan-kmind-zen](https://github.com/suka233/siyuan-kmind-zen)).

### Download

Latest preview build: <https://github.com/suka233/siyuan-kmind-zen-preview/releases/download/preview/package.zip>

Only the latest build is kept. The build time and SHA-256 checksum are in the [release notes](https://github.com/suka233/siyuan-kmind-zen-preview/releases/tag/preview).

### Install

Requires SiYuan 3.1.0 or later.

1. Download and unzip `package.zip`.
2. Open the `data/plugins/` folder of your SiYuan workspace.
3. Create the folder `siyuan-kmind-zen` (empty it first if it already exists) and put **all** extracted files in it, so that `plugin.json` sits directly inside that folder.
4. Restart SiYuan.

If you installed the stable version from the marketplace, the preview build overwrites it. To go back, reinstall the stable version from the marketplace.

### Notes

- The preview build may carry the same version number as the stable release while its content is newer.
- It includes features that are not released yet and a new data format. Mind maps saved with the preview build **may not open or be editable in the stable release or in older versions**. Do not use it on important data, and back up your workspace first.
- Like the stable version, the preview build connects to the services at `kmind.app`.
