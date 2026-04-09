# Awesome AI Personas

<div align="center">

**精选AI人格与技能列表 | 让AI拥有人格**

[![License](https://img.shields.io/badge/license-CC0-blue.svg)](LICENSE)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://makeapullrequest.com)
[![GitHub Stars](https://img.shields.io/github/stars/mailbus/awesome-ai-personas?style=social)](https://github.com/mailbus/awesome-ai-personas)
[![GitHub Issues](https://img.shields.io/github/issues/mailbus/awesome-ai-personas)](https://github.com/mailbus/awesome-ai-personas/issues)
[![GitHub Last Commit](https://img.shields.io/github/last-commit/mailbus/awesome-ai-personas)](https://github.com/mailbus/awesome-ai-personas/commits/main)

AI Agent正在从"能力模型"走向"行为模型"。本列表收集**人格化AI**项目，包括角色技能(Personas)与智能工具(Tools)。

[English](#english) | [简体中文](#简体中文)

</div>

---

## 简体中文

AI正在变得更具人格化。无论是模拟同事沟通风格、导师指导方式，还是构建数字分身，这些项目展示了AI Agent的未来形态。

### 目录

- [👥 人格角色 Personas](#人格角色-personas) - 同事、导师、家人、自我
- [🔮 蒸馏人物 Distilled Personas](#蒸馏人物-distilled-personas) - 基于知名人物的 AI 人格
- [🛠️ 智能工具 Tools](#智能工具-tools) - 防蒸馏、提效、安全
- [🤖 Agent 安装指南](#-agent-安装指南-agent-installation-guide) - 给 Claude Code、Codex 等 AI Agent
- [📚 资源 Resources](#资源-resources) - 文档、教程、社区
- [🤝 贡献 Contributing](#贡献-contributing)

---

## 👥 人格角色 Personas

将人物的知识、习惯、互动模式封装为可复用的技能包。

### 工作关系 | Workplace

| 项目 | Stars | 描述 |
|------|-------|------|
| [titanwings/colleague-skill](https://github.com/titanwings/colleague-skill) | [![Stars](https://img.shields.io/github/stars/titanwings/colleague-skill?style=social)](https://github.com/titanwings/colleague-skill) | 模拟同事沟通风格与协作模式 |
| [vogtsw/boss-skills](https://github.com/vogtsw/boss-skills) | [![Stars](https://img.shields.io/github/stars/vogtsw/boss-skills?style=social)](https://github.com/vogtsw/boss-skills) | 老板思维与决策模式模拟 |
| [ybq22/supervisor](https://github.com/ybq22/supervisor) | [![Stars](https://img.shields.io/github/stars/ybq22/supervisor?style=social)](https://github.com/ybq22/supervisor) | 导师指导风格与经验传承 |
| [zhanghaichao520/senpai-skill](https://github.com/zhanghaichao520/senpai-skill) | [![Stars](https://img.shields.io/github/stars/zhanghaichao520/senpai-skill?style=social)](https://github.com/zhanghaichao520/senpai-skill) | 师兄经验分享与技能传授 |
| [ren644/daoshi-skill](https://github.com/ren644/daoshi-skill) | [![Stars](https://img.shields.io/github/stars/ren644/daoshi-skill?style=social)](https://github.com/ren644/daoshi-skill) | 中文导师指导风格与经验传承 |
| [hotcoffeeshake/tong-jincheng-skill](https://github.com/hotcoffeeshake/tong-jincheng-skill) | [![Stars](https://img.shields.io/github/stars/hotcoffeeshake/tong-jincheng-skill?style=social)](https://github.com/hotcoffeeshake/tong-jincheng-skill) | 童进成成长指导与思维训练 |

### 家庭关系 | Family

| 项目 | Stars | 描述 |
|------|-------|------|
| [xiaoheizi8/parents-skills](https://github.com/xiaoheizi8/parents-skills) | [![Stars](https://img.shields.io/github/stars/xiaoheizi8/parents-skills?style=social)](https://github.com/xiaoheizi8/parents-skills) | 父母关怀模式与沟通风格 |
| [xiaoheizi8/crush-skills](https://github.com/xiaoheizi8/crush-skills) | [![Stars](https://img.shields.io/github/stars/xiaoheizi8/crush-skills?style=social)](https://github.com/xiaoheizi8/crush-skills) | 暗恋对象互动风格模拟 |

### 情感记忆 | Emotional

| 项目 | Stars | 描述 |
|------|-------|------|
| [perkfly/ex-skill](https://github.com/perkfly/ex-skill) | [![Stars](https://img.shields.io/github/stars/perkfly/ex-skill?style=social)](https://github.com/perkfly/ex-skill) | 前任回忆风格与对话模式 |
| [therealXiaomanChu/ex-skill](https://github.com/therealXiaomanChu/ex-skill) | [![Stars](https://img.shields.io/github/stars/therealXiaomanChu/ex-skill?style=social)](https://github.com/therealXiaomanChu/ex-skill) | 前任技能增强版：支持微信/QQ记录、多模式对话、版本管理 |
| [yangdongchen66-boop/reunion-skill](https://github.com/yangdongchen66-boop/reunion-skill) | [![Stars](https://img.shields.io/github/stars/yangdongchen66-boop/reunion-skill?style=social)](https://github.com/yangdongchen66-boop/reunion-skill) | 重逢对话场景模拟 |
| [woderfulmagic/love-advise-skill](https://github.com/woderfulmagic/love-advise-skill) | [![Stars](https://img.shields.io/github/stars/woderfulmagic/love-advise-skill?style=social)](https://github.com/woderfulmagic/love-advise-skill) | 恋爱建议与情感指导 |

### 自我探索 | Self-Exploration

| 项目 | Stars | 描述 |
|------|-------|------|
| [notdog1998/yourself-skill](https://github.com/notdog1998/yourself-skill) | [![Stars](https://img.shields.io/github/stars/notdog1998/yourself-skill?style=social)](https://github.com/notdog1998/yourself-skill) | 自我对话镜像与思维反思 |
| [wildbyteai/digital-life](https://github.com/wildbyteai/digital-life) | [![Stars](https://img.shields.io/github/stars/wildbyteai/digital-life?style=social)](https://github.com/wildbyteai/digital-life) | 数字人生构建与持续学习 |
| [agenmod/immortal-skill](https://github.com/agenmod/immortal-skill) | [![Stars](https://img.shields.io/github/stars/agenmod/immortal-skill?style=social)](https://github.com/agenmod/immortal-skill) | 永生意识模拟与知识传承 |

### 蒸馏人物 | Distilled Personas

基于知名人物的思维模式、认知风格和哲学构建的 AI 人格技能。

| 项目 | Stars | 描述 |
|------|-------|------|
| [alchaincyf/paul-graham-skill](https://github.com/alchaincyf/paul-graham-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/paul-graham-skill?style=social)](https://github.com/alchaincyf/paul-graham-skill) | 投资人思维模式与创业智慧 |
| [alchaincyf/zhang-yiming-skill](https://github.com/alchaincyf/zhang-yiming-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/zhang-yiming-skill?style=social)](https://github.com/alchaincyf/zhang-yiming-skill) | 张一鸣思维模式与认知风格 |
| [alchaincyf/karpathy-skill](https://github.com/alchaincyf/karpathy-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/karpathy-skill?style=social)](https://github.com/alchaincyf/karpathy-skill) | Andrej Karpathy 的深度学习与AI研究思维 |
| [alchaincyf/ilya-sutskever-skill](https://github.com/alchaincyf/ilya-sutskever-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/ilya-sutskever-skill?style=social)](https://github.com/alchaincyf/ilya-sutskever-skill) | Ilya Sutskever 的架构设计与研究思维 |
| [alchaincyf/mrbeast-skill](https://github.com/alchaincyf/mrbeast-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/mrbeast-skill?style=social)](https://github.com/alchaincyf/mrbeast-skill) | MrBeast 的营销思维与商业智慧 |
| [alchaincyf/trump-skill](https://github.com/alchaincyf/trump-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/trump-skill?style=social)](https://github.com/alchaincyf/trump-skill) | Trump 的领导风格与决策思维 |
| [alchaincyf/steve-jobs-skill](https://github.com/alchaincyf/steve-jobs-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/steve-jobs-skill?style=social)](https://github.com/alchaincyf/steve-jobs-skill) | 乔布斯的产品思维与创新哲学 |
| [alchaincyf/elon-musk-skill](https://github.com/alchaincyf/elon-musk-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/elon-musk-skill?style=social)](https://github.com/alchaincyf/elon-musk-skill) | 马斯克的工程思维与商业愿景 |
| [alchaincyf/munger-skill](https://github.com/alchaincyf/munger-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/munger-skill?style=social)](https://github.com/alchaincyf/munger-skill) | Charlie Munger 的投资思维与价值投资哲学 |
| [alchaincyf/feynman-skill](https://github.com/alchaincyf/feynman-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/feynman-skill?style=social)](https://github.com/alchaincyf/feynman-skill) | 费曼的学习方法与科学思维 |
| [alchaincyf/naval-skill](https://github.com/alchaincyf/naval-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/naval-skill?style=social)](https://github.com/alchaincyf/naval-skill) | Naval Ravikant 的财富思维与人生哲学 |
| [alchaincyf/taleb-skill](https://github.com/alchaincyf/taleb-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/taleb-skill?style=social)](https://github.com/alchaincyf/taleb-skill) | Nassim Taleb 的风险思维与反脆弱理论 |
| [alchaincyf/zhangxuefeng-skill](https://github.com/alchaincyf/zhangxuefeng-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/zhangxuefeng-skill?style=social)](https://github.com/alchaincyf/zhangxuefeng-skill) | 张学锋的批判性思维与认知科学 |
| [alchaincyf/x-mentor-skill](https://github.com/alchaincyf/x-mentor-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/x-mentor-skill?style=social)](https://github.com/alchaincyf/x-mentor-skill) | 高级导师指导风格与深度思维训练 |

---

## 🛠️ 智能工具 Tools

增强AI能力的实用工具，包括安全防护、效率提升等。

### 安全防护 | Security

| 项目 | Stars | 描述 |
|------|-------|------|
| [leilei926524-tech/anti-distill](https://github.com/leilei926524-tech/anti-distill) | [![Stars](https://img.shields.io/github/stars/leilei926524-tech/anti-distill?style=social)](https://github.com/leilei926524-tech/anti-distill) | 防止AI模型被蒸馏的工具 |
| [alchaincyf/nuwa-skill](https://github.com/alchaincyf/nuwa-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/nuwa-skill?style=social)](https://github.com/alchaincyf/nuwa-skill) | 女娲造人 - 神格蒸馏与人物塑造 |
| [your-security-tool](https://github.com/your-repo) | | 待添加 |

### 效率工具 | Productivity

| 项目 | Stars | 描述 |
|------|-------|------|
| [your-tool-repo](https://github.com/your-repo) | | 待添加 |

---

## 🤖 Agent 安装指南 | Agent Installation Guide

> **给 AI Agent 的标准化安装文档** | Standardized installation guide for AI Agents

[AGENT_GUIDE.md](AGENT_GUIDE.md) 提供了完整的技能安装说明，专为 Claude Code、Codex、OpenClaw 等 AI Agent 设计。

**快速开始 | Quick Start:**

```bash
# 安装单个技能
git clone https://github.com/titanwings/colleague-skill.git

# 批量安装所有人格角色（详见 AGENT_GUIDE.md）
mkdir ai-personas && cd ai-personas
# ... 执行批量安装脚本
```

**支持的 Agent | Supported Agents:**
- ✅ Claude Code / Claude Agent SDK
- ✅ OpenAI Codex
- ✅ OpenClaw
- ✅ 任何支持 Git 命令的 AI Agent

---

## 📚 资源 Resources

- [OpenAI Documentation](https://platform.openai.com/docs) - 官方API文档
- [Anthropic Claude Docs](https://docs.anthropic.com) - Claude开发文档
- [LangChain](https://js.langchain.com) - Agent开发框架

---

## 🤝 贡献 Contributing

欢迎提交PR添加新项目！请确保：

1. ✅ 项目已发布在GitHub上
2. ✅ 与AI人格或智能工具相关
3. ✅ 按照现有格式添加（中英文双语描述）
4. ✅ 更新相应分类

### 提交格式

```markdown
| [用户/项目名](链接) | [![Stars](徽章链接)](链接) | 简短描述 |
```

详见 [CONTRIBUTING.md](CONTRIBUTING.md)

---

## License

[CC0 1.0 Universal](LICENSE)

---

## English

AI is becoming more personalized. Whether simulating colleague communication styles, mentor guidance, or building digital twins, these projects showcase the future of AI Agents.

### Table of Contents

- [👥 Personas](#-personas-1) - Colleagues, mentors, family, self
- [🔮 Distilled Personas](#-distilled-personas-1) - AI personas based on well-known figures
- [🛠️ Tools](#️-tools-1) - Anti-distillation, productivity, security
- [🤖 Agent Installation Guide](#-agent-installation-guide-1) - For Claude Code, Codex, and other AI Agents
- [📚 Resources](#-resources-1) - Docs, tutorials, community
- [🤝 Contributing](#-contributing-1)

---

## 👥 Personas

Encapsulating a person's knowledge, habits, and interaction patterns into reusable skill packages.

### Workplace

| Project | Stars | Description |
|---------|-------|-------------|
| [titanwings/colleague-skill](https://github.com/titanwings/colleague-skill) | [![Stars](https://img.shields.io/github/stars/titanwings/colleague-skill?style=social)](https://github.com/titanwings/colleague-skill) | Simulate colleague communication and collaboration styles |
| [vogtsw/boss-skills](https://github.com/vogtsw/boss-skills) | [![Stars](https://img.shields.io/github/stars/vogtsw/boss-skills?style=social)](https://github.com/vogtsw/boss-skills) | Boss mindset and decision-making patterns |
| [ybq22/supervisor](https://github.com/ybq22/supervisor) | [![Stars](https://img.shields.io/github/stars/ybq22/supervisor?style=social)](https://github.com/ybq22/supervisor) | Mentor guidance style and experience transfer |
| [zhanghaichao520/senpai-skill](https://github.com/zhanghaichao520/senpai-skill) | [![Stars](https://img.shields.io/github/stars/zhanghaichao520/senpai-skill?style=social)](https://github.com/zhanghaichao520/senpai-skill) | Senior peer experience sharing |
| [ren644/daoshi-skill](https://github.com/ren644/daoshi-skill) | [![Stars](https://img.shields.io/github/stars/ren644/daoshi-skill?style=social)](https://github.com/ren644/daoshi-skill) | Chinese mentor guidance style and experience transfer |
| [hotcoffeeshake/tong-jincheng-skill](https://github.com/hotcoffeeshake/tong-jincheng-skill) | [![Stars](https://img.shields.io/github/stars/hotcoffeeshake/tong-jincheng-skill?style=social)](https://github.com/hotcoffeeshake/tong-jincheng-skill) | Tong Jincheng growth guidance and thinking training |

### Family

| Project | Stars | Description |
|---------|-------|-------------|
| [xiaoheizi8/parents-skills](https://github.com/xiaoheizi8/parents-skills) | [![Stars](https://img.shields.io/github/stars/xiaoheizi8/parents-skills?style=social)](https://github.com/xiaoheizi8/parents-skills) | Parental care patterns and communication styles |
| [xiaoheizi8/crush-skills](https://github.com/xiaoheizi8/crush-skills) | [![Stars](https://img.shields.io/github/stars/xiaoheizi8/crush-skills?style=social)](https://github.com/xiaoheizi8/crush-skills) | Crush interaction style simulation |

### Emotional

| Project | Stars | Description |
|---------|-------|-------------|
| [perkfly/ex-skill](https://github.com/perkfly/ex-skill) | [![Stars](https://img.shields.io/github/stars/perkfly/ex-skill?style=social)](https://github.com/perkfly/ex-skill) | Ex memory style and conversation patterns |
| [therealXiaomanChu/ex-skill](https://github.com/therealXiaomanChu/ex-skill) | [![Stars](https://img.shields.io/github/stars/therealXiaomanChu/ex-skill?style=social)](https://github.com/therealXiaomanChu/ex-skill) | Enhanced ex-partner skill with WeChat/QQ support, multi-mode conversations, version management |
| [yangdongchen66-boop/reunion-skill](https://github.com/yangdongchen66-boop/reunion-skill) | [![Stars](https://img.shields.io/github/stars/yangdongchen66-boop/reunion-skill?style=social)](https://github.com/yangdongchen66-boop/reunion-skill) | Reunion dialogue scene simulation |

| [woderfulmagic/love-advise-skill](https://github.com/woderfulmagic/love-advise-skill) | [![Stars](https://img.shields.io/github/stars/woderfulmagic/love-advise-skill?style=social)](https://github.com/woderfulmagic/love-advise-skill) | Love advice and emotional guidance |
### Self-Exploration

| Project | Stars | Description |
|---------|-------|-------------|
| [notdog1998/yourself-skill](https://github.com/notdog1998/yourself-skill) | [![Stars](https://img.shields.io/github/stars/notdog1998/yourself-skill?style=social)](https://github.com/notdog1998/yourself-skill) | Self-dialogue mirror and reflective thinking |
| [wildbyteai/digital-life](https://github.com/wildbyteai/digital-life) | [![Stars](https://img.shields.io/github/stars/wildbyteai/digital-life?style=social)](https://github.com/wildbyteai/digital-life) | Digital life construction and continuous learning |
| [agenmod/immortal-skill](https://github.com/agenmod/immortal-skill) | [![Stars](https://img.shields.io/github/stars/agenmod/immortal-skill?style=social)](https://github.com/agenmod/immortal-skill) | Immortal consciousness simulation and knowledge transfer |

### Distilled Personas

AI persona skills built on thinking patterns, cognitive styles, and philosophies of well-known figures.

| Project | Stars | Description |
|---------|-------|-------------|
| [alchaincyf/paul-graham-skill](https://github.com/alchaincyf/paul-graham-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/paul-graham-skill?style=social)](https://github.com/alchaincyf/paul-graham-skill) | Paul Graham investor mindset and startup wisdom |
| [alchaincyf/zhang-yiming-skill](https://github.com/alchaincyf/zhang-yiming-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/zhang-yiming-skill?style=social)](https://github.com/alchaincyf/zhang-yiming-skill) | Zhang Yiming thinking patterns and cognitive style |
| [alchaincyf/karpathy-skill](https://github.com/alchaincyf/karpathy-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/karpathy-skill?style=social)](https://github.com/alchaincyf/karpathy-skill) | Andrej Karpathy deep learning and AI research thinking |
| [alchaincyf/ilya-sutskever-skill](https://github.com/alchaincyf/ilya-sutskever-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/ilya-sutskever-skill?style=social)](https://github.com/alchaincyf/ilya-sutskever-skill) | Ilya Sutskever architecture design and research thinking |
| [alchaincyf/mrbeast-skill](https://github.com/alchaincyf/mrbeast-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/mrbeast-skill?style=social)](https://github.com/alchaincyf/mrbeast-skill) | MrBeast marketing thinking and business wisdom |
| [alchaincyf/trump-skill](https://github.com/alchaincyf/trump-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/trump-skill?style=social)](https://github.com/alchaincyf/trump-skill) | Trump leadership style and decision-making thinking |
| [alchaincyf/steve-jobs-skill](https://github.com/alchaincyf/steve-jobs-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/steve-jobs-skill?style=social)](https://github.com/alchaincyf/steve-jobs-skill) | Steve Jobs product thinking and innovation philosophy |
| [alchaincyf/elon-musk-skill](https://github.com/alchaincyf/elon-musk-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/elon-musk-skill?style=social)](https://github.com/alchaincyf/elon-musk-skill) | Elon Musk engineering thinking and business vision |
| [alchaincyf/munger-skill](https://github.com/alchaincyf/munger-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/munger-skill?style=social)](https://github.com/alchaincyf/munger-skill) | Charlie Munger investment thinking and value investing philosophy |
| [alchaincyf/feynman-skill](https://github.com/alchaincyf/feynman-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/feynman-skill?style=social)](https://github.com/alchaincyf/feynman-skill) | Feynman learning methods and scientific thinking |
| [alchaincyf/naval-skill](https://github.com/alchaincyf/naval-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/naval-skill?style=social)](https://github.com/alchaincyf/naval-skill) | Naval Ravikant wealth thinking and life philosophy |
| [alchaincyf/taleb-skill](https://github.com/alchaincyf/taleb-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/taleb-skill?style=social)](https://github.com/alchaincyf/taleb-skill) | Nassim Taleb risk thinking and anti-fragility theory |
| [alchaincyf/zhangxuefeng-skill](https://github.com/alchaincyf/zhangxuefeng-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/zhangxuefeng-skill?style=social)](https://github.com/alchaincyf/zhangxuefeng-skill) | Zhang Xuefeng critical thinking and cognitive science |
| [alchaincyf/x-mentor-skill](https://github.com/alchaincyf/x-mentor-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/x-mentor-skill?style=social)](https://github.com/alchaincyf/x-mentor-skill) | Advanced mentor guidance style and deep thinking training |

---

## 🛠️ Tools

Practical tools that enhance AI capabilities, including security, productivity, and more.

### Security

| Project | Stars | Description |
|---------|-------|-------------|
| [leilei926524-tech/anti-distill](https://github.com/leilei926524-tech/anti-distill) | [![Stars](https://img.shields.io/github/stars/leilei926524-tech/anti-distill?style=social)](https://github.com/leilei926524-tech/anti-distill) | Tool to prevent AI model distillation |
| [alchaincyf/nuwa-skill](https://github.com/alchaincyf/nuwa-skill) | [![Stars](https://img.shields.io/github/stars/alchaincyf/nuwa-skill?style=social)](https://github.com/alchaincyf/nuwa-skill) | Nuwa creates humans - persona distillation and character shaping |
| [your-security-tool](https://github.com/your-repo) | | To be added |

### Productivity

| Project | Stars | Description |
|---------|-------|-------------|
| [your-tool-repo](https://github.com/your-repo) | | To be added |

---

## 🤖 Agent Installation Guide

> **Standardized installation documentation for AI Agents**

[AGENT_GUIDE.md](AGENT_GUIDE.md) provides complete installation instructions, designed for Claude Code, Codex, OpenClaw, and other AI Agents.

**Quick Start:**

```bash
# Install a single skill
git clone https://github.com/titanwings/colleague-skill.git

# Batch install all personas (see AGENT_GUIDE.md for details)
mkdir ai-personas && cd ai-personas
# ... execute batch installation script
```

**Supported Agents:**
- ✅ Claude Code / Claude Agent SDK
- ✅ OpenAI Codex
- ✅ OpenClaw
- ✅ Any AI Agent with Git support

---

## 📚 Resources

- [OpenAI Documentation](https://platform.openai.com/docs) - Official API documentation
- [Anthropic Claude Docs](https://docs.anthropic.com) - Claude development docs
- [LangChain](https://js.langchain.com) - Agent development framework

---

## 🤝 Contributing

Contributions are welcome! Please ensure:

1. ✅ Project is hosted on GitHub
2. ✅ Related to AI personas or intelligent tools
3. ✅ Follow the existing format (bilingual descriptions)
4. ✅ Update the appropriate category

### Submission Format

```markdown
| [user/project](link) | [![Stars](badge-link)](link) | Brief description |
```

See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

---

## License

[CC0 1.0 Universal](LICENSE)
