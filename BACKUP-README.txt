百忧解项目本机备份

source/baiyoujie-next：当前开发源代码，具体完成与验证范围请参阅进度文档。
source/baiyoujie-next/docs/PROGRESS.md：最新进度、已确认要求、测试记录和后续任务。
requirements：用户提供的两份需求文档。
artifacts/user-supplied-original.apk：用户原始安装包（如存在）。
artifacts/latest-available-development.apk：备份时可用的最近开发版构建产物，具体验证范围请参阅进度文档。
verification：构建与测试日志。
MANIFEST.json：每个归档文件的 SHA-256 校验值。

恢复：解压到新目录，用 Android Studio 打开 source/baiyoujie-next，重新设置本机 Android SDK 路径并同步依赖，然后按进度文档继续。
未包含：编译缓存、Git 历史、本机 SDK/JDK、local.properties、常见密钥文件、模拟器中的聊天数据和系统状态。
此包仅保存在当前电脑，不是远程备份。请另存一份到外部存储。