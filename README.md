# BiliDownloader

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Rust Version](https://img.shields.io/badge/rust-1.75%2B-orange.svg)

🚀 一个使用Rust编写的哔哩哔哩视频命令行下载器。

## ✨ 特性

- 🔒 **安全登录**
  - 支持二维码扫码登录
  - 支持 Cookie 登录
  - 自动保存登录状态

- 🚄 **高性能下载**
  - 异步并发下载
  - 支持进度显示
  - 自动合并音视频

- 🎯 **智能解析**
  - 支持 DASH 流媒体
  - 支持 FLV 格式
  - 自动选择最优清晰度

- 🛠 **便捷功能**
  - 命令行友好界面
  - 清晰的下载进度
  - 可配置下载路径

## 📝 命令行参数

```bash
选项：
    --login              启用登录模式
    --url               视频链接
    --output            下载目录
    --quality           视频质量
    --user-dir          用户配置目录
```

## 🔧 编译

```bash
git clone https://github.com/rpeng666/bilidl
cd bilidl
cargo build --release
```


## ⭐ 支持项目

如果这个项目对你有帮助，请给它一个 Star！
