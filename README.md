<p align="center">
  <img src="./assets/hero-banner.png" alt="Nexus Ones Hero Banner" width="100%">
</p>

<h1 align="center">Nexus Ones</h1>

<p align="center">
  <strong>Personal Operating Hub</strong>
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

## 产品定位

Nexus Ones 是一套面向个人用户的工作与生活秩序系统（Personal Operating Hub）。

它并不是单纯的待办软件，也不是单纯的日历软件。

Nexus Ones 试图把：

- 日历 Calendar
- 待办 Tasks
- 提醒 Reminders
- 备忘 Notes
- 项目 Projects
- 课程 Course Center
- 插件 Plugins

统一到一个稳定、轻量、可扩展的个人工作台之中。

---

## 快速入口

<p align="center">
  <img src="./assets/download.png" width="120">
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="./assets/plugin.png" width="120">
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="./assets/document.png" width="120">
</p>

<p align="center">
  Download Center &nbsp;&nbsp;&nbsp;&nbsp;
  Plugin Center &nbsp;&nbsp;&nbsp;&nbsp;
  Documentation
</p>

<br>

<p align="center">
  <img src="./assets/feedback.png" width="120">
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="./assets/contact.png" width="120">
</p>

<p align="center">
  Feedback Center &nbsp;&nbsp;&nbsp;&nbsp;
  Contact
</p>

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

---

### Calendar

支持：

- 年视图
- 月视图
- 周视图
- 日视图

包含：

- 中国节假日
- 农历显示
- 日程管理
- 提醒联动

---

### Tasks & Reminders

统一任务系统：

- 待办
- 提醒
- 项目事项
- 备忘事项

优先级体系：

| 等级 | 含义 |
|------|------|
| P1 | 非常重要 |
| P2 | 重要 |
| P3 | 普通 |
| P4 | 不重要 |

---

### Four Quadrants

自动根据：

- P等级
- 时间紧迫性

动态计算：

- 重要且紧急
- 重要不紧急
- 不重要但紧急
- 不重要不紧急

无需手动维护四象限。

---

### Course Center

课程管理中心：

- 手动创建课表
- Excel导入课表
- 课程提醒
- 学期管理

适用于：

- 教师
- 学生
- 培训机构

---

### Project Library

统一管理：

- 教学项目
- 科研项目
- 软件开发
- 比赛项目
- 个人计划

---

### Status Light

Nexus Ones 核心视觉系统。

状态灯：

- 绿色
- 黄色
- 红色

支持：

- 呼吸灯
- 脉冲灯
- 状态预警
- Hover 信息

用于快速感知：

- 今日截止事项
- 即将逾期事项
- 高优先级事项
- 数据状态异常

---

## 插件系统（Plugin Runtime）

v0.2.4 开始正式实装 Plugin Runtime。

支持：

- HTML 插件
- JavaScript 插件
- 本地数据存储
- Runtime Sandbox
- 插件消息机制

插件格式：

```text
hello.nexus
```

未来版本将开放：

- Plugin SDK
- Plugin Marketplace
- Plugin Store

---

## Update Center

支持：

- 检查更新
- 更新公告
- update.json
- GitHub Release

未来版本将逐步完善：

- 自动下载
- 自动安装
- 增量更新

---

## Snapshot & Restore

内置快照系统。

支持：

- 创建快照
- 恢复快照
- 回滚
- 恢复校验

用于保护用户数据安全。

---

## 数据安全

Nexus Ones 所有业务数据均独立于应用本体。

目录结构：

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
- 卸载重装可恢复
- 插件独立存储
- 快照独立管理

---

## 跨设备工作流

推荐数据目录：

```text
iCloud Drive
└── Nexus Ones Data
```

支持：

```text
Mac mini
     ↓
 iCloud
     ↓
MacBook Air
```

实现跨设备同步工作。

---

## 公测计划

Nexus Ones v0.2.4 Beta

World Cup 2026 Edition

本轮测试重点：

- Plugin Runtime
- Update Center
- Snapshot & Restore
- 数据目录管理
- Status Light
- 跨设备同步

感谢所有参与测试的用户。

---

## 技术架构

Frontend

```text
React
TypeScript
Vite
```

Backend

```text
Tauri 2
Rust
SQLite
```

Platforms

```text
macOS
Windows
```

---

## 下载

### macOS

```text
Nexus Ones.dmg
```

### Windows

```text
Nexus Ones Setup.exe
```

---

## 开发

```bash
pnpm install

pnpm tauri dev
```

构建：

```bash
pnpm tauri build
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

## Nexus Lab

Designed and developed by Nexus Lab.

Building software for productivity, education and personal operating systems.

---

## License

Copyright © Nexus Lab

All Rights Reserved.
