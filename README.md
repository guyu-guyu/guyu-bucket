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

<!-- APPS_TABLE_BEGIN -->
| 应用 | 描述 | 版本 |
|------|------|------|
| [autovideocompressor](https://github.com/guyu-guyu/AutoVideoCompressor) | 视频素材定时压缩工具 — 自动扫描目录、调用 ffmpeg 压缩、支持 Per-directory 配置和 cron 调度 | 0.3.4 |
| [schedulecenter](https://github.com/guyu-guyu/scheduleCenter) | Windows 定时任务管理中心 — WPF GUI + CLI 双模式，管理 Windows 任务计划程序 | 0.1.1 |
<!-- APPS_TABLE_END -->

## 许可证

MIT
