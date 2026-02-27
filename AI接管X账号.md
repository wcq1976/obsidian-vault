---
source: bosshuman (xman.ink)
created: 2026-02-27
category: AI工具
tags: [X, Twitter, API, AI, 自动化]
---

# 让 AI Agent 接管你的 X 账号

> 来源：xman.ink | 智能推特书签管理平台

## 痛点

- X 官方 API 太贵：Basic $100/月，Pro $5000/月
- 只想发推、搜推、收藏

## 方案

做一个本地 API 服务，AI Agent 直接操控 X 账号

**优点：**
- 不需要 X 官方 API
- 不需要付费
- 不需要申请开发者账号
- 全程本地运行，数据不经过第三方

## 3 分钟上手

### 第 1 步：导出 Cookies
1. Chrome 登录 x.com
2. 装 Cookie-Editor 扩展
3. 点扩展图标 → Export → 保存为 cookies.json

### 第 2 步：启动服务
把 cookies.json 丢进来，终端显示 ✅ Cookie 登录成功

### 第 3 步：配置 OpenClaw
直接说话：
- "帮我搜一下最近关于 Cursor 的推文"
- "帮我发一条推"
- "帮我收藏这条推"

## 能做什么

- 发推
- 搜索
- 点赞
- 收藏

## 风险说明

### 会封号吗？
风险很低。频率控制：
- 每小时不超过 30 次
- 每天不超过 200 次
- 发推一天 10-20 条

### Cookies 会过期吗？
会，几周到几个月不等。过期重新导出，30 秒搞定。

## 相关链接

- GitHub：https://github.com/bosshuman/openclaw-x
- Skill：https://clawhub.ai/bosshuman/openclaw-x

## 评价

比 CDP 更轻量，零 API 费用。适合需要偶尔操作 X 的场景。
