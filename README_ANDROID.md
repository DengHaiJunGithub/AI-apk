# AI 转型学习助手（Android）

这是将原网页封装成离线 Android WebView 应用的工程。学习内容内置在 APK 中；勾选记录保存在应用本地，网页提供 JSON 进度导入/导出。

## 构建 APK

需要 Android Studio 和 Android SDK Platform 35。打开本项目目录，等待 Gradle 同步，然后选择 **Build > Build APK(s)**。APK 默认生成于 `app/build/outputs/apk/debug/app-debug.apk`。

也可在已安装 Gradle 和 Android SDK 的命令行环境运行 `gradle assembleDebug`。首次构建需要联网下载 Android Gradle Plugin 和 SDK 组件。安装 debug APK 时，Android 可能要求允许“安装未知应用”。
