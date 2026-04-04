# AI Agent 安装指南 | AI Agent Installation Guide

> **给 AI Agent 的说明文档** | Documentation for AI Agents

本文档专为 AI Agent（Claude Code、Codex、OpenClaw 等）设计，提供标准化的技能安装指令。

---

## 📋 使用说明 | Instructions

**当用户要求安装技能时：**

1. **单一技能** - 直接安装对应仓库
2. **批量安装** - 询问用户需要哪几类，然后批量安装
3. **技能详情** - 展示技能列表供用户选择

---

## 🎯 技能列表 | Skills List

### 👥 人格角色 | Personas

| 技能名 | 仓库 | 描述 | 安装命令 |
|--------|------|------|----------|
| 同事技能 | titanwings/colleague-skill | 模拟同事沟通风格与协作模式 | `git clone https://github.com/titanwings/colleague-skill.git` |
| 老板技能 | vogtsw/boss-skills | 老板思维与决策模式模拟 | `git clone https://github.com/vogtsw/boss-skills.git` |
| 导师技能 | ybq22/supervisor | 导师指导风格与经验传承 | `git clone https://github.com/ybq22/supervisor.git` |
| 师兄技能 | zhanghaichao520/senpai-skill | 师兄经验分享与技能传授 | `git clone https://github.com/zhanghaichao520/senpai-skill.git` |
git clone https://github.com/ren644/daoshi-skill.git
| 中文导师技能 | ren644/daoshi-skill | 中文导师指导风格与经验传承 | `git clone https://github.com/ren644/daoshi-skill.git` |
| 父母技能 | xiaoheizi8/parents-skills | 父母关怀模式与沟通风格 | `git clone https://github.com/xiaoheizi8/parents-skills.git` |
| 暗恋对象技能 | xiaoheizi8/crush-skills | 暗恋对象互动风格模拟 | `git clone https://github.com/xiaoheizi8/crush-skills.git` |
| 前任技能 | perkfly/ex-skill | 前任回忆风格与对话模式 | `git clone https://github.com/perkfly/ex-skill.git` |
git clone https://github.com/therealXiaomanChu/ex-skill.git
| 前任技能增强版 | therealXiaomanChu/ex-skill | 支持微信/QQ记录、多模式对话、版本管理 | `git clone https://github.com/therealXiaomanChu/ex-skill.git` |
| 重逢技能 | yangdongchen66-boop/reunion-skill | 重逢对话场景模拟 | `git clone https://github.com/yangdongchen66-boop/reunion-skill.git` |
git clone https://github.com/woderfulmagic/love-advise-skill.git
| 自己技能 | notdog1998/yourself-skill | 自我对话镜像与思维反思 | `git clone https://github.com/notdog1998/yourself-skill.git` |
| 恋爱建议技能 | woderfulmagic/love-advise-skill | 恋爱建议与情感指导 | `git clone https://github.com/woderfulmagic/love-advise-skill.git` |
| 数字人生 | wildbyteai/digital-life | 数字人生构建与持续学习 | `git clone https://github.com/wildbyteai/digital-life.git` |
| 永生技能 | agenmod/immortal-skill | 永生意识模拟与知识传承 | `git clone https://github.com/agenmod/immortal-skill.git` |

### 🛠️ 智能工具 | Tools

| 技能名 | 仓库 | 描述 | 安装命令 |
|--------|------|------|----------|
| 防蒸馏工具 | leilei926524-tech/anti-distill | 防止AI模型被蒸馏的工具 | `git clone https://github.com/leilei926524-tech/anti-distill.git` |

---

## 🚀 快速安装模板 | Quick Install Templates

### 安装单个技能 | Install Single Skill

```bash
# 示例：安装同事技能
git clone https://github.com/titanwings/colleague-skill.git
cd colleague-skill
# 查看技能内的 README.md 了解使用方法
cat README.md
```

### 批量安装人格角色 | Batch Install Personas

```bash
#!/bin/bash
# 创建技能目录
mkdir -p ai-personas
cd ai-personas

# 工作关系
git clone https://github.com/titanwings/colleague-skill.git
git clone https://github.com/vogtsw/boss-skills.git
git clone https://github.com/ybq22/supervisor.git
git clone https://github.com/zhanghaichao520/senpai-skill.git
git clone https://github.com/ren644/daoshi-skill.git

# 家庭关系
git clone https://github.com/xiaoheizi8/parents-skills.git
git clone https://github.com/xiaoheizi8/crush-skills.git

# 情感记忆
git clone https://github.com/perkfly/ex-skill.git
git clone https://github.com/therealXiaomanChu/ex-skill.git
git clone https://github.com/yangdongchen66-boop/reunion-skill.git
git clone https://github.com/woderfulmagic/love-advise-skill.git

# 自我探索
git clone https://github.com/notdog1998/yourself-skill.git
git clone https://github.com/wildbyteai/digital-life.git
git clone https://github.com/agenmod/immortal-skill.git

echo "✅ 所有人格角色技能已安装到 ai-personas 目录"
```

### 批量安装工具 | Batch Install Tools

```bash
#!/bin/bash
# 创建工具目录
mkdir -p ai-tools
cd ai-tools

# 安全工具
git clone https://github.com/leilei926524-tech/anti-distill.git

echo "✅ 所有工具已安装到 ai-tools 目录"
```

---

## 📦 Agent 执行流程 | Agent Execution Flow

### 当用户说 "安装所有技能" | When user says "Install all skills"

```python
# Agent 伪代码
def install_all_skills():
    # 1. 创建目录
    create_directory("ai-skills")
    
    # 2. 克隆所有仓库
    repos = [
        "titanwings/colleague-skill",
        "vogtsw/boss-skills",
        "ybq22/supervisor",
        "zhanghaichao520/senpai-skill",
git clone https://github.com/ren644/daoshi-skill.git
        "xiaoheizi8/parents-skills",
        "xiaoheizi8/crush-skills",
        "perkfly/ex-skill",
        "yangdongchen66-boop/reunion-skill",
git clone https://github.com/woderfulmagic/love-advise-skill.git
        "notdog1998/yourself-skill",
        "wildbyteai/digital-life",
        "agenmod/immortal-skill",
        "leilei926524-tech/anti-distill"
    ]
    
    for repo in repos:
        run(f"git clone https://github.com/{repo}.git")
    
    # 3. 报告结果
    print("✅ 所有技能已安装完成！")
```

### 当用户说 "安装工作相关技能" | When user says "Install workplace skills"

```bash
# 工作关系类技能
git clone https://github.com/titanwings/colleague-skill.git
git clone https://github.com/vogtsw/boss-skills.git
git clone https://github.com/ybq22/supervisor.git
git clone https://github.com/zhanghaichao520/senpai-skill.git
git clone https://github.com/ren644/daoshi-skill.git
```

### 当用户说 "安装情感相关技能" | When user says "Install emotional skills"

```bash
# 情感记忆类技能
git clone https://github.com/perkfly/ex-skill.git
git clone https://github.com/therealXiaomanChu/ex-skill.git
git clone https://github.com/yangdongchen66-boop/reunion-skill.git
git clone https://github.com/woderfulmagic/love-advise-skill.git
git clone https://github.com/xiaoheizi8/crush-skills.git
```

---

## 🔧 安装后配置 | Post-Install Configuration

每个技能安装后，Agent 应该：

1. **读取 README.md** - 了解技能用途和使用方法
2. **检查配置文件** - 查看是否需要 API 密钥或环境变量
3. **验证依赖** - 确认所需依赖已安装
4. **测试运行** - 按照技能文档进行测试

```bash
# 安装后检查流程示例（以同事技能为例）
cd colleague-skill

# 1. 查看说明
cat README.md

# 2. 检查是否有配置文件
ls -la | grep -E "(config|env|settings)"

# 3. 查看是否有依赖文件
if [ -f "requirements.txt" ]; then
    pip install -r requirements.txt
fi

if [ -f "package.json" ]; then
    npm install
fi
```

---

## 📚 技能分类速查 | Skills Category Quick Reference

| 分类 | 关键词 | 包含技能 |
|------|--------|----------|
| 工作关系 | work, workplace, colleague, boss, supervisor | 同事, 老板, 导师, 师兄 |
| 家庭关系 | family, parent, crush | 父母, 暗恋对象 |
| 情感记忆 | emotional, ex, reunion | 前任, 重逢 |
| 自我探索 | self, digital-life, immortal | 自己, 数字人生, 永生 |
| 安全工具 | security, anti-distill | 防蒸馏 |

---

## 🌐 在线资源 | Online Resources

- **完整列表**: https://github.com/mailbus/awesome-ai-personas
- **更新日志**: https://github.com/mailbus/awesome-ai-personas/commits/main
- **提交新技能**: https://github.com/mailbus/awesome-ai-personas/issues/new

---

## 💡 Agent 使用提示 | Tips for Agents

1. **并行安装** - 使用多线程并行下载多个仓库以提升速度
2. **错误处理** - 如果某个仓库克隆失败，记录错误但继续安装其他技能
3. **空间检查** - 安装前检查磁盘空间是否充足
4. **目录结构** - 建议将技能按分类存放到不同子目录

```bash
# 推荐的目录结构
ai-skills/
├── personas/
│   ├── workplace/
│   ├── family/
│   ├── emotional/
│   └── self-exploration/
└── tools/
    ├── security/
    └── productivity/
```

---

*本文档由 AI Agent 自动维护 | This document is automatically maintained by AI Agents*

*最后更新 | Last Updated: 2026-04-04*
