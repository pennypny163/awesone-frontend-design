# 🎨 Awesome Design — 全球顶级品牌设计系统库

> 精心收集的 **68 个世界级品牌设计规范**。一站式获取 Apple、Stripe、Notion、Linear 等品牌的完整设计系统，快速构建符合品牌美学的高质量 UI。

![Awesome Design](https://img.shields.io/badge/design%20systems-68%20brands-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue) ![Language](https://img.shields.io/badge/language-Chinese%20%2F%20English-blueviolet)

---

## ✨ 核心特性

### 📦 完整的设计规范
每个品牌都包含 **9 个完整的设计模块**：
- 🎭 视觉气质与设计理念
- 🎨 颜色系统（语义化命名 + HEX 值）
- 🔤 排版体系（字体层级、行高、字重）
- 🔘 组件样式库（按钮、卡片、输入框、导航等）
- 📐 布局与间距系统
- 🌑 深度隐喻与阴影系统
- ⚡ 响应式设计规则
- ✅ 最佳实践与反模式指南
- 🤖 AI 生成提示词模板

### 🚀 即插即用
- 无需从零开始设计
- 直接复制颜色值、字体配置、间距尺度
- 适配所有前端框架（React、Vue、Svelte）
- 支持 Web、小程序、移动端

### 🎯 覆盖各行业
从硅谷科技巨头到创意工具，从金融科技到电商平台，提供多元化的设计参考。

---

## 🏢 涵盖的品牌（68 个）

### 🤖 AI 与大模型平台
Claude、Cohere、ElevenLabs、Minimax、Mistral、Ollama、Replicate、RunwayML、Voltagent、OpenCode.ai、Together.ai、X.ai

### 👨‍💻 开发者工具 & IDE
Cursor、Expo、Lovable、Mintlify、Raycast、Vercel、Warp

### 💾 后端 / 数据库 / DevOps
ClickHouse、HashiCorp、MongoDB、PostHog、Sanity、Sentry、Supabase

### 📱 生产力工具 & SaaS
Cal、Intercom、Linear.app、Notion、Resend、Superhuman、Zapier

### 🎨 设计与创意工具
Airtable、Figma、Framer、Miro、Webflow

### 💰 金融科技 & 加密货币
Binance、Coinbase、Kraken、Mastercard、Revolut、Stripe、Wise

### 🏪 电商 & 零售
Pinterest、Shopify、Uber

### 🚗 豪车品牌
BMW、Bugatti、Ferrari、Lamborghini、Porsche、Tesla

### 📺 科技与消费
Apple、IBM、Meta、Microsoft、Nike、Nvidia、PlayStation、Spotify、Vodafone

### 📰 媒体与内容
TheVerge、Wired

### 🔧 更多品牌
Airbnb、Binance、Figma、Warp、和更多...

---

## 🚀 快速开始

### 1️⃣ 浏览品牌设计规范

```bash
# 打开任意品牌的设计文件
cat references/notion/DESIGN.md
cat references/stripe/DESIGN.md
cat references/linear.app/DESIGN.md
```

### 2️⃣ 选择你的目标品牌

根据要构建的 UI 气质选择参考品牌：

| 设计气质 | 推荐品牌 |
|---------|---------|
| 🌙 暗色、极简、工程感 | Linear.app、Cursor、Warp |
| ☀️ 温暖、编辑感、清爽 | Claude、Notion、Cal |
| ⚡ 大胆、活力、消费级 | Nike、Spotify、Uber |
| 👑 高端、豪华、不易接近 | Ferrari、Lamborghini、BMW |
| 🔧 开发者、技术向 | Vercel、Supabase、HashiCorp |
| 💳 金融、信任、精准 | Stripe、Revolut、Wise |
| 🎨 俏皮、创意、多彩 | Figma、Framer、Miro |
| 🏢 企业、专业、稳重 | IBM、MongoDB、Intercom |
| 🚀 未来感、科幻 | SpaceX、Nvidia、Tesla |

### 3️⃣ 提取设计令牌

从选定的 DESIGN.md 中提取：

```json
{
  "colors": {
    "primary": "#3B82F6",
    "secondary": "#10B981",
    "bg": "#0F172A"
  },
  "typography": {
    "fontFamily": "Inter, -apple-system, BlinkMacSystemFont",
    "headings": { "size": "32px", "weight": 700 }
  },
  "spacing": {
    "xs": "4px",
    "sm": "8px",
    "md": "16px",
    "lg": "24px"
  }
}
```

### 4️⃣ 应用到你的项目

在 CSS、Tailwind、StyledComponents 中使用这些令牌，快速构建看起来专业、一致的 UI。

---

## 📖 使用场景

### ✅ 何时使用本库

- 📌 **品牌风格参考**："用 Notion 的风格做个页面"
- 🎯 **设计系统学习**：研究顶级科技公司的设计决策
- 🔄 **快速原型设计**：在设计阶段快速确定视觉方向
- 🤖 **辅助 AI 生成**：为 AI 工具提供精确的设计约束
- 📱 **多品牌项目**：为不同客户提供多种设计风格
- 🎓 **设计教学**：理解企业级设计系统的构成要素

### 🚫 何时不使用

- 直接抄袭品牌设计（尊重知识产权）
- 替代专业设计师的创意工作

---

## 📁 项目结构

```
awesome-design/
├── README.md                 # 项目说明（本文件）
├── SKILL.md                  # 技能定义文档
└── references/               # 设计规范目录
    ├── notion/
    │   └── DESIGN.md         # Notion 完整设计规范
    ├── stripe/
    │   └── DESIGN.md         # Stripe 完整设计规范
    ├── linear.app/
    │   └── DESIGN.md
    └── ... （66 个品牌）
```

---

## 💡 使用建议

### 针对前端开发者
1. 阅读 "Color Palette" 部分，复制颜色变量
2. 查看 "Typography System"，设置全局字体配置
3. 参考 "Component Styles"，编写组件库
4. 遵循 "Do's & Don'ts"，保持设计一致性

### 针对产品设计师
1. 研究 "Visual Theme & Atmosphere"，理解品牌调性
2. 学习色彩系统的语义化命名方式
3. 观察 "Responsive Behavior"，适配各种屏幕
4. 提取 "Do's & Don'ts"，建立设计规范

### 针对 AI/LLM 用户
- 在 "Agent Prompt Guide" 部分找到预制的 AI 生成提示词
- 直接复制到 ChatGPT、Claude 等工具生成代码

---

## 🎁 包含的特殊内容

### 每个 DESIGN.md 都包含：

✅ **完整的颜色方案** — 精确的 HEX 值，分类清晰  
✅ **排版层级表** — 所有尺寸、行高、字重  
✅ **组件示例** — 按钮、表单、卡片、导航、模态框  
✅ **间距标度** — 4px、8px、16px... 的使用规则  
✅ **阴影系统** — 深度隐喻和视觉分层  
✅ **响应式规则** — 移动端、平板、桌面端的适配  
✅ **设计禁忌** — 什么不应该做  
✅ **AI 提示词** — 直接用于生成代码的魔法短语  

---

## 🎯 常见问题

**Q: 我能否直接在商业项目中使用这些颜色？**  
A: 这个库是为学习和参考而设计的。颜色和设计概念可以学习应用，但请尊重原品牌的知识产权。

**Q: 这些设计规范有多新？**  
A: 库会持续更新。建议定期 star ⭐ 并关注新版本。

**Q: 支持哪些框架？**  
A: 设计令牌是通用的，可用于任何框架（React、Vue、Svelte、Vanilla JS、移动端等）。

**Q: 如何向库中添加新品牌？**  
A: 欢迎提交 PR！按照现有的 DESIGN.md 格式提交新品牌即可。

---

## 🌟 为什么使用这个库？

| 对比维度 | 传统方式 | Awesome Design |
|---------|---------|----------------|
| ⏱️ 设计时间 | 数天 | 数小时 |
| 📚 学习成本 | 高 | 低 |
| 📊 准确性 | 参差不齐 | 企业级标准 |
| 🎨 视觉质量 | 取决于设计师 | 顶级品牌水准 |
| 🔄 复用性 | 低 | 高 |

---

## 📞 联系与反馈

- 🐛 发现问题？提交 [Issue](https://github.com/pennypny163/awesone-frontend-design/issues)
- 💡 有好的建议？提交 PR 或讨论
- ⭐ 觉得有用？请给个 Star！

---

## 📄 许可证

MIT License — 自由使用、修改、分发。

---

## 🙏 致谢

感谢所有参与设计系统研究和贡献的人。  
本库灵感来自这 68 个世界级品牌的卓越设计。

---

## 🚀 下一步

- ⭐ Star 此项目，获得更新通知
- 🔖 Bookmark 本库，作为设计参考
- 📤 分享给你的设计师和开发者朋友
- 💬 在社区反馈和改进

**让我们一起打造更美的数字产品！** 🎨✨
