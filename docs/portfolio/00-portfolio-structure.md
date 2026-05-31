# 作品集整合说明

## 文件信息

- **作品集主文件**：`smart-campus-inspection-portfolio.md`
- **用途**：PM实习面试作品集，可导出为PDF
- **目标页数**：30-50页（Markdown估算，每页约500-800字）
- **作者**：林泣渝（LaneQiyu）
- **日期**：2026-04-27

---

## 作品集结构

| 章节 | 内容 | 预估页数 | 对应源文件 |
|------|------|---------|-----------|
| **封面** | 项目名称、副标题、作者、日期 | 1 | — |
| **第一章：项目概述** | 背景与痛点、项目目标、核心创新点、个人角色 | 3-4 | `prd/01-background-and-goals.md` |
| **第二章：用户研究** | 5个用户画像精选、3份旅程地图、关键洞察 | 4-5 | `user-research/01-personas.md`, `02-journey-maps.md` |
| **第三章：竞品分析** | 竞品对比矩阵精简版、差异化定位、关键发现 | 3-4 | `competitive-analysis/comparison-matrix.md` |
| **第四章：场景设计** | 3个核心场景流程图、闭环设计、SLA与升级策略 | 6-8 | `prd/03-scenario-overview.md`, `04/05/06-scenario-*.md` |
| **第五章：PRD精要** | 需求规格摘要、非功能需求与SLA矩阵、版本规划 | 4-5 | `prd/07-nonfunctional-requirements.md`, `08-version-roadmap.md` |
| **第六章：架构设计** | 系统架构图、数据流图、部署架构、C4模型 | 5-6 | `architecture/01/03/04-*.md` |
| **第七章：原型展示** | 设计系统概述、移动端关键页面、PC端关键页面 | 6-8 | `design/figma-exports/00/01/03-*.md` |
| **第八章：总结反思** | 项目亮点回顾、局限性与未来方向、个人收获 | 2-3 | — |
| **附录** | 文档索引、术语表 | 1-2 | — |

---

## 整合原则

1. **精选不堆砌**：从源文件中提取核心观点和数据，不做全文复制
2. **图表文字化**：所有架构图、流程图、原型图用文字描述+表格表示，便于Markdown转PDF
3. **数据驱动**：关键指标用引用块标注，增强说服力
4. **叙事连贯**：以"问题→方案→验证→反思"的主线串联各章节
5. **页数控制**：总计约30-50页，确保面试时可快速翻阅

---

## 生成PDF建议

1. 使用 **Typora** 或 **VS Code + Markdown PDF插件** 导出
2. 页面设置：A4，页边距 2.5cm
3. 字体建议：正文 11pt，标题按层级递减
4. 图表处理：Markdown表格在PDF中自动渲染，无需额外处理
5. 目录：导出时自动生成书签/目录

---

## 源文件清单

| 源文件路径 | 在作品集中的用途 |
|-----------|----------------|
| `docs/prd/01-background-and-goals.md` | 第一章背景与目标 |
| `docs/user-research/01-personas.md` | 第二章用户画像 |
| `docs/user-research/02-journey-maps.md` | 第二章旅程地图 |
| `docs/competitive-analysis/comparison-matrix.md` | 第三章竞品分析 |
| `docs/prd/03-scenario-overview.md` | 第四章场景概述 |
| `docs/prd/04-scenario-daily-inspection.md` | 第四章日常巡检场景 |
| `docs/prd/05-scenario-equipment-inspection.md` | 第四章设备检查场景 |
| `docs/prd/06-scenario-emergency-response.md` | 第四章应急事件场景 |
| `docs/prd/07-nonfunctional-requirements.md` | 第五章非功能需求与SLA |
| `docs/prd/08-version-roadmap.md` | 第五章版本规划 |
| `docs/architecture/01-system-architecture.md` | 第六章系统架构 |
| `docs/architecture/03-deployment-architecture.md` | 第六章部署架构 |
| `docs/architecture/04-c4-model.md` | 第六章C4模型 |
| `design/figma-exports/00-design-system.md` | 第七章设计系统 |
| `design/figma-exports/01-mobile-daily-inspection.md` | 第七章移动端原型 |
| `design/figma-exports/03-pc-dashboard-and-workorder.md` | 第七章PC端原型 |
