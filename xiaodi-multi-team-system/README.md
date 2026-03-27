# 🤖 小弟多团队协作系统

<p align="center">
  <strong>专业的 AI Agent 团队协作系统</strong>
</p>

<p align="center">
  <strong>4 大功能团队 · 26 个专业 Agent · 1 个智能切换器</strong>
</p>

<p align="center">
  <a href="#-团队介绍">团队介绍</a> •
  <a href="#-快速开始">快速开始</a> •
  <a href="#-系统架构">系统架构</a> •
  <a href="#-配置说明">配置说明</a> •
  <a href="#-使用示例">使用示例</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.1-blue.svg" alt="Version">
  <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="License">
  <img src="https://img.shields.io/badge/OpenClaw-Compatible-purple.svg" alt="OpenClaw">
</p>

---

## ✨ 核心特性

| 特性 | 说明 |
|------|------|
| 🔄 **智能团队切换** | 自动识别用户意图，一键切换金融、电商、多媒体、办公场景 |
| 🤝 **多 Agent 协作** | Master-Worker 架构，角色分工明确，协作完成复杂任务 |
| 📊 **完整工作流编排** | 支持多步骤任务流程，自动调度各角色协作 |
| 🔐 **安全的 API 管理** | 环境变量配置，无硬编码密钥，支持多种 AI 服务 |
| 🌐 **多数据源支持** | 东方财富、腾讯财经、亚马逊、TikTok 等公开 API |
| 🎬 **多媒体处理** | 视频压缩、字幕生成、图片处理、音频转码 |

---

## 📦 团队介绍

### 📊 金融分析师团队

**7 大专业角色协作**

| 角色 | 职责 | 核心能力 |
|------|------|----------|
| 💼 投顾专家 | 综合服务、统筹协调 | 投资组合、风险评估 |
| 🔬 行业研究员 | 产业链分析、机会挖掘 | 行业研究、竞品分析 |
| 🏦 投行专家 | 并购重组、IPO 辅导 | 资本运作、估值建模 |
| 📈 市值管理助理 | IR 策略、资本运作 | 投资者关系、市值策略 |
| 💰 财富专员 | 资产配置、基金筛选 | 财富规划、基金优选 |
| 🎯 商机助理 | 交易信号、买卖时机 | 技术分析、量化信号 |
| 📰 舆情助理 | 舆情监测、风险预警 | 新闻分析、情绪监控 |

**数据源**：东方财富、腾讯财经、新浪财经（均为公开 API）

---

### 🛒 电商运营团队

**8 大专业角色协作**

| 角色 | 职责 | 核心能力 |
|------|------|----------|
| 🔍 选品专家 | 选品分析、爆款挖掘 | BSR 分析、趋势追踪、销量预估 |
| 📊 运营专员 | 店铺运营、数据分析 | 流量分析、转化优化、活动策划 |
| 💵 定价专员 | 价格策略、利润计算 | 动态定价、成本核算、ROI 分析 |
| 💬 客服专员 | 客户服务、评价管理 | 智能回复、投诉处理、FAQ 生成 |
| 📈 数据分析师 | 数据采集、报表生成 | 多源整合、趋势预测、异常预警 |
| 🎯 竞品分析师 | 竞品监控、差异化分析 | 价格追踪、差评挖掘、策略建议 |
| ✍️ 内容创作者 | 商品文案、Listing | SEO 优化、标题生成、详情页 |
| 📢 投放专员 | 广告投放、ROI 优化 | 多平台投放、预算优化、效果分析 |

**支持平台**：亚马逊、TikTok Shop、小红书

---

### 🎬 多媒体处理团队

**7 大专业角色协作**

| 角色 | 职责 | 核心能力 |
|------|------|----------|
| 🎬 视频剪辑师 | 视频剪辑、压缩、转码 | ffmpeg 处理、格式转换 |
| 🎥 视频创作师 | AI 视频生成 | 可灵、Runway、Pika、Sora |
| 📝 字幕生成器 | 自动生成字幕 | Whisper 语音识别 |
| 🖼️ 图片处理师 | 图片压缩、转换、缩放 | ImageMagick 处理 |
| 🎨 AI 绘图师 | AI 生成图片 | DALL-E、Stable Diffusion |
| 🎵 音频处理师 | 音频转码、提取 | ffmpeg 音频处理 |
| 📊 质量检查员 | 文件质量检查 | ffprobe 分析 |

**依赖工具**：ffmpeg、ImageMagick、Whisper（可选）

---

### 📋 办公秘书团队

**4 大专业角色协作**

| 角色 | 职责 | 核心能力 |
|------|------|----------|
| 📅 日程秘书 | 日程管理、提醒 | 日程添加、查询、提醒 |
| 📧 邮件秘书 | 邮件处理、分类 | 邮件摘要、分类整理 |
| 📄 文档秘书 | 文档管理、整理 | 格式转换、内容整理 |
| 🎤 会议秘书 | 会议记录、纪要 | 实时记录、纪要生成 |

---

## 🚀 快速开始

### 安装

```bash
# 通过 ClawHub 安装
clawhub install xiaodi-multi-team-system

# 或从 GitHub 克隆
git clone https://github.com/mx6315909/xiaodi-multi-team-skills.git
cd xiaodi-multi-team-skills
```

### 系统要求

```bash
# 安装必需依赖
# Ubuntu/Debian
sudo apt install ffmpeg imagemagick

# macOS
brew install ffmpeg imagemagick

# Python 包
pip install requests akshare  # akshare 可选
```

### 使用示例

```
# 金融场景
分析茅台的投资价值
诊断我的持仓：茅台 100股、宁德时代 200股

# 电商场景
帮我选品，类目：美妆护肤，优先跨境
监控这个产品的竞品价格变化

# 多媒体场景
压缩这个视频 /path/to/video.mp4
生成一个视频：猫咪在阳光下打盹

# 办公场景
帮我安排明天下午3点的会议
整理这份文档，生成会议纪要
```

---

## 🏗️ 系统架构

```
┌─────────────────────────────────────────────────────────────┐
│                    xiaodi-multi-team-system                  │
│                      多团队协作系统                           │
├─────────────────────────────────────────────────────────────┤
│                                                              │
│  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐          │
│  │ 📊 金融团队  │  │ 🛒 电商团队  │  │ 🎬 多媒体   │          │
│  │             │  │             │  │    团队     │          │
│  │ 7 Agents    │  │ 8 Agents    │  │ 7 Agents    │          │
│  └─────────────┘  └─────────────┘  └─────────────┘          │
│                                                              │
│  ┌─────────────┐  ┌─────────────────────────────────────┐   │
│  │ 📋 办公团队  │  │        🔄 团队切换器                │   │
│  │             │  │  智能识别用户意图，自动切换团队      │   │
│  │ 4 Agents    │  └─────────────────────────────────────┘   │
│  └─────────────┘                                            │
│                                                              │
├─────────────────────────────────────────────────────────────┤
│                        底层能力层                            │
│  web_search │ web_fetch │ exec │ browser │ memory_search   │
├─────────────────────────────────────────────────────────────┤
│                        数据源层                              │
│  东方财富 │ 腾讯财经 │ 亚马逊 │ TikTok │ 新浪财经          │
└─────────────────────────────────────────────────────────────┘
```

---

## ⚙️ 配置说明

### 可选 API 配置

AI 视频生成功能需要配置以下环境变量（可选）：

```bash
# 可灵 AI
export KLING_API_KEY=your_key

# Runway Gen-3
export RUNWAY_API_KEY=your_key

# Pika Labs
export PIKA_API_KEY=your_key

# OpenAI (Sora/DALL-E)
export OPENAI_API_KEY=your_key
```

### 工具权限

| 工具 | 用途 | 风险等级 |
|------|------|----------|
| `web_search` | 网络搜索 | 🟢 低 |
| `web_fetch` | 获取网页内容 | 🟢 低 |
| `memory_search` | 搜索记忆 | 🟢 低 |
| `exec` | 执行系统命令 | 🟡 中（仅限媒体处理工具） |
| `browser` | 浏览器自动化 | 🟡 中（仅限公开网页） |

---

## 📁 项目结构

```
xiaodi-multi-team-system/
├── SKILL.md                    # 技能定义文件
├── clawhub.json                # ClawHub 元数据
├── REQUIREMENTS.md             # 依赖说明
├── LICENSE                     # MIT License
└── teams/
    ├── xiaodi-financial-team/  # 金融团队
    │   ├── agents/             # 7 个 Agent 定义
    │   ├── scripts/            # 股票分析脚本
    │   └── ...
    ├── xiaodi-ecom-team/       # 电商团队
    │   ├── scripts/            # 选品、监控脚本
    │   └── ...
    ├── xiaodi-media-team/      # 多媒体团队
    │   ├── scripts/            # 视频、图片处理脚本
    │   └── ...
    ├── xiaodi-office-team/     # 办公团队
    │   ├── scripts/            # 会议、文档脚本
    │   └── ...
    └── xiaodi-team-switcher/   # 团队切换器
        └── ...
```

---

## 🔐 安全声明

- ✅ **无硬编码密钥**：所有 API Key 通过环境变量配置
- ✅ **公开数据源**：仅使用公开 API，无需认证
- ✅ **受限 exec**：仅用于 ffmpeg、ImageMagick 等媒体处理工具
- ✅ **无数据外传**：不读取主机敏感文件，不外传用户数据
- ✅ **透明代码**：所有脚本开源可审计

---

## 🗺️ 开发路线图

- [x] v1.0.0 - 初始发布，4 大团队 + 切换器
- [x] v1.0.1 - 添加依赖声明，改进安全配置
- [ ] v1.1.0 - 添加更多数据源支持
- [ ] v1.2.0 - 支持自定义 Agent 角色
- [ ] v2.0.0 - 跨平台 GUI 管理界面

---

## 🤝 贡献指南

欢迎贡献代码、报告问题或提出建议！

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 创建 Pull Request

---

## 📄 License

本项目采用 MIT License 开源协议 - 详见 [LICENSE](LICENSE) 文件

---

## 👤 作者

**xiaodi**

- Email: mxbot-xiaodi@agentmail.to
- GitHub: [@mx6315909](https://github.com/mx6315909)

---

## 🙏 致谢

- [OpenClaw](https://github.com/openclaw/openclaw) - AI Agent 框架
- [ClawHub](https://clawhub.ai) - Agent 技能市场
- [ffmpeg](https://ffmpeg.org) - 多媒体处理
- [ImageMagick](https://imagemagick.org) - 图片处理
- [akshare](https://github.com/akfamily/akshare) - A股数据

---

<p align="center">
  <strong>如果觉得有用，请给一个 ⭐️ Star！</strong>
</p>

<p align="center">
  Made with ❤️ by xiaodi
</p>