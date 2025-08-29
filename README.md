# SideCalendar

[中文](https://github.com/sha2kyou/SideCalendar/blob/main/README.md) | [English](https://github.com/sha2kyou/SideCalendar/blob/main/README_EN.md)

**SideCalendar**是一款 macOS 菜单栏应用程序，将来自各种来源（日历、提醒事项、RSS、GitHub 等）的事件和信息统一到一个动态屏幕边缘信息流中。

>[!WARNING]
>本应用为闭源软件，仓库仅用于版本发布与问题反馈。  
>本应用尚处于开发阶段，可能会有一些影响使用的问题，欢迎大家提交 Issues！

## 最低运行需求
macOS 14.0 (Sonoma) 或更高版本。

## 功能

| 功能 | lite / github | pro / appstore |
| :--- | :---: | :---: |
| 价格 | 0 | $2.99（限时七折）|
| 日历和提醒事项集成 | ✅ | ✅ |
| GitHub 集成 | ❌ | ✅ |
| RSS 阅读器集成 | ❌ | ✅ |
| 插件市场 | ❌ | ✅ |
| 自定义插件 (即将推出) | ❌ | ✅ |
| iCloud 配置同步 | ❌ | ✅ |
| iOS 事件同步 (即将推出) | ❌ | ✅ |
| 高级设置 | ❌ | ✅ |

## 安装方式

### 方式一（推荐）

[![download](https://oss.tr1ck.cn/image/20250826/6VuezL.png)](https://apps.apple.com/cn/app/sidecalendar/id6751482006)

### 方式二

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
- [ ] 增加 iCloud 同步
- [ ] 增加 iOS 同步
- [ ] ~~接入 CalDav 插件~~
- [x] 接入 Github Star 插件
- [x] 接入 Github PR 插件
- [x] 完成可读性调整设置


