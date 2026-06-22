<p align="center">
  <img src="./assets/hero-banner.png" alt="Nexus Ones Hero Banner" width="100%">
</p>

<h1 align="center">Nexus Ones</h1>

<p align="center">
  <strong>Personal Operating Hub｜个人办公中枢系统</strong>
</p>

<p align="center">
  将日历、待办、提醒、备忘、项目、课程与插件统一到一个个人办公中枢系统。
</p>

<p align="center">
  <img src="https://img.shields.io/badge/macOS-Supported-black?style=for-the-badge">
  <img src="https://img.shields.io/badge/Windows-Supported-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Tauri-2.x-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge">
  <img src="https://img.shields.io/badge/Version-v0.2.4--beta.1-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/2026-World_Cup_Edition-gold?style=for-the-badge">
</p>

---

## 快速入口

<p align="center">

<a href="https://github.com/NexusMemory/nexus-ones-release/releases/latest">
  <img src="./assets/download.png" width="120" alt="Download Center">
</a>

&nbsp;&nbsp;&nbsp;&nbsp;

<a href="https://github.com/NexusMemory/nexus-ones-release/tree/main/plugins">
  <img src="./assets/plugin.png" width="120" alt="Plugin Center">
</a>

&nbsp;&nbsp;&nbsp;&nbsp;

<a href="https://github.com/NexusMemory/nexus-ones-release/tree/main/docs">
  <img src="./assets/document.png" width="120" alt="Documentation">
</a>

</p>

<p align="center">

<a href="https://github.com/NexusMemory/nexus-ones-release/releases/latest">
下载中心
</a>

&nbsp;&nbsp;&nbsp;&nbsp;

<a href="https://github.com/NexusMemory/nexus-ones-release/tree/main/plugins">
插件中心
</a>

&nbsp;&nbsp;&nbsp;&nbsp;

<a href="https://github.com/NexusMemory/nexus-ones-release/tree/main/docs">
文档中心
</a>

</p>

<br>

<p align="center">

<a href="https://github.com/NexusMemory/nexus-ones-release/issues">
  <img src="./assets/feedback.png" width="120" alt="Feedback Center">
</a>

&nbsp;&nbsp;&nbsp;&nbsp;

<a href="mailto:LeungKinWah@outlook.com">
  <img src="./assets/contact.png" width="120" alt="Contact">
</a>

</p>

<p align="center">

<a href="https://github.com/NexusMemory/nexus-ones-release/issues">
反馈建议
</a>

&nbsp;&nbsp;&nbsp;&nbsp;

<a href="mailto:LeungKinWah@outlook.com">
联系开发者
</a>

</p>

---

## 产品定位

Nexus Ones 是一套面向个人用户的工作与生活秩序系统。

它不是单一的日历、待办或备忘录工具，而是一个 Personal Operating Hub，用于把分散的信息、任务、项目、课程与插件能力统一到一个稳定的个人工作台中。

---

## 核心功能

### Today Dashboard

统一查看：

- 今日状态
- 今日提醒
- 今日待办
- 四象限任务
- 日历事项
- 项目进度
- 倒计时

### Calendar

支持：

- 年视图
- 月视图
- 周视图
- 日视图
- 中国节假日
- 农历显示
- 日程管理
- 提醒联动

### Tasks & Reminders

统一任务系统：

- 待办
- 提醒
- 项目事项
- 备忘事项

优先级体系：

| 等级 | 含义 |
|---|---|
| P1 | 非常重要 |
| P2 | 重要 |
| P3 | 普通 |
| P4 | 不重要 |

### Four Quadrants

自动根据 P 等级与时间紧迫性动态计算：

- 重要且紧急
- 重要不紧急
- 不重要但紧急
- 不重要不紧急

### Plugin Runtime

v0.2.4 开始实装 Plugin Runtime。

支持：

- HTML 插件
- JavaScript 插件
- 本地插件数据存储
- Runtime Sandbox
- 插件消息机制

示例插件：

```text
hello.nexus
```

---

## 数据安全

Nexus Ones 所有业务数据独立于应用本体。

推荐数据目录：

```text
Nexus Ones Data
├── production
├── sandbox
├── plugins
├── backups
└── config
```

优势：

- 覆盖安装不丢数据
- 卸载重装可重新识别
- 插件独立存储
- 快照独立管理
- 支持 iCloud 跨设备同步

---

## 跨设备工作流

推荐数据目录：

```text
iCloud Drive
└── Nexus Ones Data
```

典型工作流：

```text
Mac mini
     ↓
 iCloud
     ↓
MacBook Air
```

---

## 公测计划

Nexus Ones v0.2.4 Beta｜World Cup 2026 Edition

本轮测试重点：

- Plugin Runtime
- Update Center
- Snapshot & Restore
- 数据目录管理
- Status Light
- 跨设备同步
- Windows 安装体验

感谢所有参与测试的用户。

---

## 下载

最新版下载：

[Nexus Ones 最新版本](https://github.com/NexusMemory/nexus-ones-release/releases/latest)

如果 latest 页面暂不可用，请进入：

[Nexus Ones Releases](https://github.com/NexusMemory/nexus-ones-release/releases)

### macOS

```text
Nexus Ones.dmg
```

### Windows

```text
Nexus Ones Setup.exe
```

---

## 路线图

### v0.3

- Plugin Marketplace
- Desktop Widgets
- Health Center
- Plugin SDK

### v0.4

- AI Workspace
- Knowledge Hub
- Cross Device Sync Enhancement

### v1.0

- Stable Release
- Complete Plugin Ecosystem
- Nexus Ones Public Launch

---

## 技术架构

Frontend：

```text
React
TypeScript
Vite
```

Backend：

```text
Tauri 2
Rust
SQLite
```

Platforms：

```text
macOS
Windows
```

---

## Nexus Lab

Designed and developed by Nexus Lab.

Building software for productivity, education and personal operating systems.

---

## License

Copyright © Nexus Lab

All Rights Reserved.
