# 策略部门 (Strategy)

策略部门包含NEXUS框架核心文档，涵盖从发现到运营的全生命周期管理。

## 文档列表

| 文件名 | 文档名称 | 主要内容 |
|--------|----------|----------|
| nexus-strategy.md | NEXUS策略 | 7阶段管道、代理协调矩阵、质量门、交接协议 |
| EXECUTIVE-BRIEF.md | 执行简报 | 高层战略概览、关键指标 |
| QUICKSTART.md | 快速启动 | 快速激活指南、部署配置 |

## 子目录

### coordination/
协调相关文档，包含交接模板和代理激活提示。

| 文件名 | 主要内容 |
|--------|----------|
| handoff-templates.md | 标准交接文档格式、NEXUS交接模板 |
| agent-activation-prompts.md | 代理激活提示模板 |

### playbooks/
按阶段划分的操作手册，从发现到运营。

| 文件名 | 阶段 | 主要内容 |
|--------|------|----------|
| phase-0-discovery.md | 阶段0 | 情报与发现、市场验证 |
| phase-1-strategy.md | 阶段1 | 策略与架构、规范定义 |
| phase-2-foundation.md | 阶段2 | 基础与脚手架、基础设施 |
| phase-3-build.md | 阶段3 | 构建与迭代、开发↔QA循环 |
| phase-4-hardening.md | 阶段4 | 质量与加固、生产就绪 |
| phase-5-launch.md | 阶段5 | 发布与增长、市场上市 |
| phase-6-operate.md | 阶段6 | 运营与演进、持续运营 |

### runbooks/
场景化运行手册，针对特定用例。

| 文件名 | 场景 |
|--------|------|
| scenario-incident-response.md | 事件响应 |
| scenario-marketing-campaign.md | 营销活动 |
| scenario-startup-mvp.md | 创业MVP |
| scenario-enterprise-feature.md | 企业功能 |

## NEXUS七阶段管道

| 阶段 | 名称 | 目标 |
|------|------|------|
| 0 | 发现 | 情报与发现、市场验证 |
| 1 | 策略 | 定义构建内容、成功标准 |
| 2 | 基础 | 构建技术和运营基础 |
| 3 | 构建 | 通过开发↔QA循环实现功能 |
| 4 | 加固 | 质量门、生产就绪验证 |
| 5 | 发布 | 市场上市、增长渠道 |
| 6 | 运营 | 持续运营、演进优化 |

## 部署模式

| 模式 | 活跃代理 | 用例 | 时间线 |
|------|----------|------|--------|
| NEXUS-Full | 全部 | 企业产品发布 | 12-24周 |
| NEXUS-Sprint | 15-25 | 功能/MVP | 2-6周 |
| NEXUS-Micro | 5-10 | Bug修复/内容 | 1-5天 |
