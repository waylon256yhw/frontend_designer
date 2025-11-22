# Frontend Design Assistant

一个 Claude Code Skill，帮助零代码/低代码用户快速设计独特、美观的前端界面，同时在实践中学习设计概念。

## 解决什么问题

AI 生成的前端界面往往千篇一律 —— Inter 字体、紫色渐变、居中卡片布局。这种 "AI slop" 审美让人一眼就能认出是机器生成的。

这个 Skill 通过以下方式打破这种模式：

- **强制创意选择** — 禁用常见 AI 默认字体/配色，要求每个设计决策都有明确理由
- **边做边学** — 在代码中即时解释设计概念，而非提前灌输理论
- **触感交互** — 界面应该像物体一样有重量感，而非平面纸张

## 文件结构

```
├── SKILL.md                           # 核心设计哲学与工作流程
└── references/
    ├── typography-guide.md            # 字体推荐（按风格分类）
    ├── color-palettes.md              # 配色方案（IDE主题/文化美学）
    ├── design-inspirations.md         # 打破常规的布局模式
    └── interaction-patterns.md        # 触感交互配方
```

## 核心原则

### 设计黑名单

| 类别 | 禁用 |
|------|------|
| 字体 | Inter, Roboto, Arial, Open Sans, Space Grotesk |
| 配色 | 紫色渐变、企业蓝灰、柔和粉彩 |
| 布局 | 居中三卡片、等权重特性网格 |
| 动效 | `transition: all 0.3s ease` |

### 交互六式

1. **The Squeeze** — 按钮按压缩放
2. **The Spotlight** — 鼠标追踪发光
3. **The Texture** — 数字噪点颗粒
4. **The Stagger** — 交错入场动画
5. **The Blur** — 毛玻璃深度层
6. **The Snappy** — 物理真实缓动

## 使用方式

将此 Skill 安装到 Claude Code 后，以下请求会自动触发：

- "帮我设计一个个人作品集页面"
- "做一个深色主题的仪表盘"
- "CSS Grid 是什么意思？"

Claude 会先声明设计决策，再生成带内联解释的代码。

## 适用人群

- 想快速出原型但不想要"AI味"的设计师
- 学习前端但被术语困扰的新手
- 需要独特视觉风格的个人项目

## License

MIT
