# TraceFlow Downloads

TraceFlow 是 Windows x64 Android Perfetto 采集工具。本仓库只存放公开下载包和 Release，不包含 TraceFlow 源码。

## 下载

- [最新 Release](https://github.com/guohuan78/TraceFlow-Downloads/releases/latest)
- [最新版本更新清单](https://github.com/guohuan78/TraceFlow-Downloads/releases/latest/download/update.json)

下载后请解压整个目录，再运行 `TraceFlow.exe`。包内包含 .NET 运行时，但需要自行准备 Android SDK Platform-Tools 提供的 `adb.exe`。

## 校验与安全

每个版本同时提供 ZIP 的 SHA-256 校验文件。正式 CI 发布包中的 `.exe` 和 `.dll` 使用 Windows Authenticode 签名；下载后请保留完整目录，不要只复制单个 EXE。

源码仓库为 private：<https://github.com/guohuan78/TraceFlow>