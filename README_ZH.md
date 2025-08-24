# SideCalendar

[中文](https://github.com/sha2kyou/SideCalendar/blob/main/README_ZH.md) | [English](https://github.com/sha2kyou/SideCalendar/blob/main/README.md)

**SideCalendar**是一款 macOS 菜单栏应用程序，将来自各种来源（日历、提醒事项、RSS、GitHub 等）的事件和信息统一到一个动态屏幕边缘信息流中。

>[!WARNING]
>本应用为闭源软件，仓库仅用于版本发布与问题反馈。  
>本应用尚处于开发阶段，可能会有一些影响使用的问题，欢迎大家提交 Issues！

## 最低运行需求
macOS 14.0 (Sonoma) 或更高版本。

## 安装方式

### 方式一（推荐）

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

你订阅的事件会在屏幕边缘以彩条的形式呈现。

<img width="3842" height="2162" alt="1Capture_2025-08-22_20 48 14" src="https://github.com/user-attachments/assets/e2a66ac0-0586-481e-baad-b9add99795a1" />

如果你事件比较多，彩条甚至会连成一道彩虹！

<img width="3842" height="2162" alt="1Capture_2025-08-22_20 52 51" src="https://github.com/user-attachments/assets/41288a69-5724-42b7-bb2f-cd0ef5c857fd" />

还有简易气泡模式，适合只想看动态不想关注详情的情况。

<img width="3842" height="2162" alt="1Capture_2025-08-23_13 14 06" src="https://github.com/user-attachments/assets/f00c6c45-a4a7-4847-b02c-f771f2622b91" />

## 待办项

- [x] 完善插件框架
- [x] 优化多插件加载性能
- [x] 完成插件市场接入，并设置默认插件
- [x] 完成多插件异步加载
- [ ] 加入自定义插件功能
- [ ] 接入 CalDav 插件
- [x] 接入 Github Star 插件
- [x] 接入 Github PR 插件
- [x] 完成可读性调整设置


