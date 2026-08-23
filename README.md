# 硬核网游攻略库 (MMO Guides)

[![Deploy to GitHub Pages](https://github.com/mhxuxubaobao/mmo/actions/workflows/pages/badge.svg)](https://mhxuxubaobao.github.io/mmo/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

这是一个专注于大型多人在线游戏（MMO）深度机制拆解与进阶玩法的综合类静态攻略站点。本仓库致力于沉淀高质量、通用型的游戏攻略内容，并通过自动化构建流部署至 GitHub Pages。

🌐 **站点地址**: [https://mhxuxubaobao.github.io/mmo](https://mhxuxubaobao.github.io/mmo)

---

## 📖 内容定位

本站拒绝浅尝辄止，专注于高价值的长尾搜索需求与硬核机制剖析。内容主要涵盖以下维度：

*   **副本与首领机制解析**：高难副本开荒路线规划、核心机制应对策略与团队协作指南。
*   **职业进阶与流派构建**：全职业天赋树加点思路、技能循环（Rotation）优化与装备属性收益（Stat Weights）评测。
*   **经济系统与效率指南**：游戏内市场供需分析、高效率资源采集路线与商业技能冲点攻略。
*   **系统与版本前瞻**：大型版本更新带来的底层数值变动与玩法迭代深度评测。

## ✨ 核心特性

*   **极速响应 (Fast)**：纯静态架构，依托 GitHub Pages 全球 CDN 加速，提供最流畅的阅读体验，极致优化 SEO 抓取效率。
*   **结构化数据 (SEO Friendly)**：全站采用语义化 HTML5 与规范的 Meta 标签配置，针对长尾关键词进行深度优化。
*   **自动化发布 (Automated Publishing)**：
    *   支持通过 API 令牌（Token）进行内容自动化提交。
    *   内置推送时间窗口控制（例如 `09:00-23:00`）与频率限制。
    *   通过自定义脚本模拟自然的内容更新节律，保障搜索引擎的持续高频收录。

## 📂 目录结构示例

```text
├── .github/
│   └── workflows/      # GitHub Actions 自动化部署配置
├── docs/               # 攻略文章源文件 (Markdown)
│   ├── raids/          # 副本与开荒攻略
│   ├── classes/        # 职业与流派构建
│   ├── economy/        # 经济与资源获取
│   └── mechanics/      # 底层机制与数值分析
├── public/             # 静态资源 (图片、样式、脚本)
├── index.html          # 站点首页模板
└── config.json         # 站点全局与自动化推送配置
