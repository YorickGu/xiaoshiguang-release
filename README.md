# 小时光 · 安装包发布

「小时光」Android 应用的发布仓库，存放安装包与更新清单，不含源码。

## 最新版本：3.1.3（119）

- [版本说明](https://github.com/YorickGu/xiaoshiguang-release/releases/tag/v3.1.3)
- [下载 APK](https://github.com/YorickGu/xiaoshiguang-release/releases/download/v3.1.3/xiaoshiguang-v3.1.3-release.apk)
- [SHA-256 校验文件](https://github.com/YorickGu/xiaoshiguang-release/releases/download/v3.1.3/xiaoshiguang-v3.1.3-release.apk.sha256)
- 支持 Android 6.0 及以上的 arm64 设备，沿用上一版签名，可覆盖安装并保留数据。

本版更新今天、书架、时光、知识四个页面及底部导航动效。AI 助手支持拖拽、吸附和长按语音；知识支持图片瀑布流、纯图片笔记和全屏翻页；阅读保存支持反馈与撤销。

## 应用内更新

在今天页右上角点击头像，进入「外观与更新 → 检查更新」。也可开启启动时自动检查。

清单从 jsDelivr、加速代理和 GitHub raw 依次回退获取；安装包按 update.json 中的下载源回退，并进行 SHA-256 校验。大于 20 MB 的 APK 使用 GitHub Release 附件与加速代理。

[全部版本](https://github.com/YorickGu/xiaoshiguang-release/releases)
