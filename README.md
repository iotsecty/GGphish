# GGphish 钓鱼演练平台

GGphish 是一款现代化的企业级钓鱼演练与安全意识测评平台。基于高性能后端架构与极简的前端交互设计，旨在帮助企业安全团队高效开展模拟钓鱼攻击、实时监测演练指标并生成深度 AI 复盘报告。

---

## 核心功能介绍

### 1. 仪表盘 (Dashboard)
提供全站演练指标的实时统计。涵盖活动总数、发送总量、打开率、点击率、提交率及上报率等核心数据指标的转化漏斗展示。
> ![仪表盘页面预览](https://github.com/iotsecty/GGphish/blob/main/1.dashboard-1.png)
> ![仪表盘页面预览](https://github.com/iotsecty/GGphish/blob/main/1.dashboard-2.png)

### 2. 钓鱼活动管理 (Campaign Management)
全生命周期管理演练活动。支持定时发送、多渠道模拟、实时状态追踪（运作中、已暂停、已完成）及自动化结果统计。
> ![活动列表页面预览](https://github.com/iotsecty/GGphish/blob/main/2.campaign_list.png)
> ![活动详情与诊断页面预览](https://github.com/iotsecty/GGphish/blob/main/3.campaign_detail-1.png)
> ![活动详情与诊断页面预览](https://github.com/iotsecty/GGphish/blob/main/3.campaign_detail-2.png)

### 3. 模版库 (Template Center)
- **邮件模板**：内置多种极具迷惑性的钓鱼邮件模板，支持本地化编辑与预览。
- **钓鱼模板**：模拟真实登录页（如邮件服务、OA 系统），实时捕获异常点击与信息提交行为。
> ![邮件模板页面预览](https://github.com/iotsecty/GGphish/blob/main/5.email_tpl.png)
> ![钓鱼页面模板预览](https://github.com/iotsecty/GGphish/blob/main/6.phishing_tpl.png)

### 4. 活动大屏 (Exercise Screen)
专为指挥中心或大屏展示研制。支持 3D 地球实时动效展示攻击源与受害点，动态同步演练最新进展。
> ![活动大屏预览](https://github.com/iotsecty/GGphish/blob/main/screen.png)

---

## 技术架构

### 后端 (Backend)
- **语言**：Go (Golang)
- **框架**：Gin Web Framework
- **数据库**：MySQL / SQLite (支持灵活切换)
- **核心能力**：高性能邮件异步投递、AI 报告自动化引擎、实时事件追踪。

### 前端 (Frontend)
- **语言**：TypeScript
- **框架**：Vue 3 (Composition API)
- **UI 组件库**：Element Plus
- **样式**：TailwindCSS + Vanilla CSS + CSS Variables (Design Tokens)
- **构建工具**：Vite

### 联系方式：
- **邮箱**：iotsec@163.com
- **微信**：wxid_skd7x03vugib12

© 2026 GGphish Team. 版权所有。
