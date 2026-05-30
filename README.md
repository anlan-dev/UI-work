# UI 设计作品集 · 王天娇

> **每个像素都有它的道理** —— 产品经理视角的 UI 设计，每个设计决策都有商业逻辑支撑。

## 🎯 作品概览

| # | 作品 | 风格 | 核心亮点 |
|---|------|------|----------|
| 01 | **MoneyFlow 财务仪表盘** | 扁平 + 渐变 | Z型阅读流、Progressive Disclosure、数字跳动动画 |
| 02 | **HabitFlow 健康打卡** | 暖色调 | BJ Fogg 行为模型、损失厌恶心理学、进度环动画 |
| 03 | **CloudSync SaaS 定价页** | 扁平 + 渐变 | 锚定效应、Von Restorff 效应、年付默认选中 |
| 04 | **宠伴·健康台账** | 新拟物 | 多主题切换、OCR 识别、数据看板、Excel 导出 |
| 05 | **GlobalCart 跨境电商** | 电商扁平 | 中/英/日三语 i18n、双币价格、AI 智能推荐 |
| 06 | **创作工作台** | 多主题 | 三栏布局、4 套主题、角色管理、多格式导出 |
| 07 | **Prompt Library** | 新拟物极简 | 搜索收藏、使用统计、LocalStorage 持久化 |

## 🧠 设计理念

### 四个核心原则

1. **用户优先** — 每个设计决策都从「用户需要什么」出发，而非「技术能做什么」
2. **数据驱动** — 用 A/B 测试和行为数据验证设计假设，不依赖主观审美判断
3. **心理学应用** — 锚定效应、损失厌恶、Fitts's Law——每个交互都有理论支撑
4. **效率优先** — 减少认知负荷和操作步骤，让用户用最少的思考完成任务

### 两大设计家族

| 家族 | 风格 | 适用场景 | 代表作品 |
|------|------|----------|----------|
| **A. 新拟物** | 双向阴影、柔和凹凸 | 工具类、健康类、效率类 | 宠伴、Prompt Library |
| **B. 扁平/Apple HIG** | 渐变、阴影、简洁 | 数据密集型、电商、专业工具 | MoneyFlow、CloudSync |

## 🛠 技术实现

- **CSS 变量系统** — 每个作品独立色板，统一命名规范
- **IntersectionObserver** — 滚动入场动画，分级延迟
- **requestAnimationFrame** — 数字跳动动画，easeOutCubic 缓动
- **SVG 动画** — 进度环、图标动效
- **LocalStorage** — 数据持久化（Prompt Library）
- **Chart.js** — 数据可视化（财务仪表盘、宠物台账）
- **多端适配** — 响应式设计，支持 430px 移动端到 1440px 桌面端

## 📁 项目结构

```
UIwork/
├── index.html              ← 作品集首页（暗色风格、毛玻璃导航）
├── 01-finance-dashboard.html
├── 02-health-tracker.html
├── 03-saas-pricing.html
├── 04-pet-vaccine.html
├── 05-cross-border-ai.html
├── 06-creation-cabin.html
└── 07-prompt-library.html
```

## 🚀 本地预览

```bash
# 克隆仓库
git clone https://github.com/anlan-dev/UI-work.git

# 进入目录
cd UI-work

# 用浏览器打开 index.html
# 或使用 Live Server（VS Code 插件）
```

## 📊 设计决策统计

- **作品数量**: 7 个
- **设计决策**: 30+ 个
- **心理学理论**: 12 个
- **设计风格**: 3 种（新拟物、扁平、多主题）
- **响应式断点**: 430px / 768px / 1024px / 1440px

## 🔗 相关链接

- **GitHub**: [anlan-dev/UI-work](https://github.com/anlan-dev/UI-work)
- **PM 作品集**: [anlan-dev/pm-works-demos](https://github.com/anlan-dev/pm-works-demos)
- **Email**: wangtj0212@gmail.com

---

**每个像素都有它的道理** ✨
