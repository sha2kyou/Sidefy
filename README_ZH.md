# 边缘日历

[中文](https://github.com/sha2kyou/SideCalendar/blob/main/README_ZH.md) | [English](https://github.com/sha2kyou/SideCalendar/blob/main/README.md)

**边缘日历**是一款 macOS 菜单栏应用程序，将来自各种来源（日历、提醒事项、RSS、GitHub 等）的事件和信息统一到一个动态屏幕边缘信息流中。

>[!WARNING]
>本软件为闭源软件，仓库仅用于版本发布与问题反馈。

## 最低运行需求
macOS 14.0 (Sonoma) 或更高版本。

## 安装方式

### 方式一

您可以通过 Homebrew 安装 SideCalendar。如果您尚未安装 Homebrew，请访问其官方网站获取安装指南。

安装步骤：

1. **添加 Homebrew Tap:**
    ```bash
      brew tap sha2kyou/casks
    ```

2. **安装 SideCalendar:**
   ```bash
      brew install --cask side-calendar
   ```

### 方式二

在 [Release 页面](https://github.com/sha2kyou/SideCalendar/releases/latest) 手动下载最新版，将应用拖入「应用程序」目录。

## 安装提示

若首次运行提示 *“Apple 无法验证 SideCalendar 是否包含恶意软件”*，请前往 `系统设置 → 隐私与安全性` 并选择 **仍要打开**。

## 截图

<img width="537" height="983" alt="image" src="https://github.com/user-attachments/assets/52fecad7-2b97-4f01-b319-96ac6dd9af41" />

## 待办项

- [x] 完善插件框架
- [x] 优化多插件加载性能
- [ ] 完成插件市场接入，并设置默认插件
- [ ] 完成多插件异步加载
- [ ] 加入自定义插件功能
- [ ] 接入 CalDav 插件
- [x] 接入 Github Star 插件
- [x] 接入 Github PR 插件
- [x] 完成可读性调整设置


