# guyu-bucket 🪣

我的个人 [Scoop](https://scoop.sh) bucket，收录我自己维护和常用的应用清单。

## 使用方法

```powershell
# 添加此 bucket
scoop bucket add guyu-bucket https://github.com/guyu-guyu/guyu-bucket.git

# 安装应用
scoop install guyu-bucket/<app-name>
```

## 目录结构

```
bucket/       # 应用 manifest 文件（JSON）
README.md     # 本文件
```

## 应用列表

| 应用 | 描述 | 版本 |
|------|------|------|
| schedulecenter | Windows 定时任务管理中心 — WPF GUI + CLI 双模式 | 0.1.0 |
| autocompress | 视频素材定时压缩工具（Tauri 重构版），自动扫描+ffmpeg 压缩+cron调度 | 0.1.0 |

## 许可证

MIT
