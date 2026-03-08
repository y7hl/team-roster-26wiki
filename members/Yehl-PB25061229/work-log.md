# 个人主页 - [叶鸿霖]

> 一个现代化的个人作品集网站，展示我的技能、项目和经历。

🔗 **在线访问**: [https://y7hl.github.io/team-roster-26wiki/]

## ✨ 特性
 
- 🎨 现代化设计，响应式布局
- 🌓 支持亮色/暗黑模式切换
- ⚡ 使用 React 构建，性能优异
- 📱 完美适配移动端、平板、桌面端
- 🚀 部署在 GitHub Pages

## 🛠️ 技术栈

- **框架**: React 18
- **构建工具**: Vite
- **路由**: React Router v6
- **样式**: CSS3 + CSS Modules
- **部署**: GitHub Pages

## 📂 项目结构

\`\`\`
src/
├── components/    # 可复用组件
├── pages/         # 页面
├── hooks/         # 自定义hook
├── data/          # 数据
├── images/        # 图片
└── styles/        # 样式
\`\`\`

## 🎨 设计参考

本项目的设计灵感来源于：

1. [Adham Dannaway](https://www.adhamdannaway.com/) - Header样式与动画

## 🤖 AI 协作记录

### 使用的 AI 工具
- **GitHub Copilot**: 代码补全和重构建议
- **ChatGPT**: 问题解答和代码优化

### 主要协作场景

#### 1. 响应式布局实现
**问题**: 如何让导航栏在移动端和桌面端有不同表现
**AI 帮助**: 提供了css的解决方案，提供了参考的断点值
**我的修改**: 根据开发者界面中对不同设备的模拟，调整了断点值以及部分间距
**学到的知识**: 开发者界面中可以模拟不同设备大小，便于修改响应式布局

#### 2. React 状态管理与主题系统设计
**问题**: 多个组件（Header、Hero、Footer 等）需要共享暗黑模式状态，且刷新页面后仍需保持当前主题。
**AI 帮助**: 建议使用 Context API 统一管理全局主题状态，并提供了 ThemeProvider 的基本实现思路。
**我的修改与优化**: 结合自定义 Hook 封装了 `useTheme` 逻辑，将主题状态持久化到 `localStorage`  
**学到的知识**:  
- Context Provider 的设计思想  
- 状态提升与全局状态管理的区别  
- 如何用 CSS 变量构建主题系统  

### AI 使用心得

1. AI 能快速提供解决思路，但有不懂的地方应及时询问并理解
2. 对于复杂需求，要分步骤提问，逐步完善
3. AI 生成的代码需要根据实际项目调整和优化

## 🚀 本地运行

\`\`\`bash
# 克隆项目
git clone https://github.com/y7hl/team-roster-26wiki.git

# 进入目录
cd team-roster-26wiki

# 安装依赖
npm install

# 启动开发服务器
npm run dev

# 构建生产版本
npm run build
\`\`\`

访问 `http://localhost:5173` 查看项目。

## 📦 部署

\`\`\`bash
# 部署到 GitHub Pages
npm run deploy
\`\`\`

## 📄 开源协议

MIT License

---

**联系我**: [email@example.com](mailto:yhl0903@mail.ustc.edu.cn)
\`\`\`

## ✅ 验收标准

在提交前，请对照以下清单自查：

### 功能完整性
- [1 ] 所有必需页面都已完成
- [ 1] 路由正常工作，无 404
- [ 1] 暗黑模式切换正常
- [ 1] 响应式布局在各设备上正常

### 代码质量
- [1 ] 组件拆分合理
- [ 1] 代码有适当注释
- [ 1] 无 console.log 等调试代码
- [ 1] 无 ESLint 错误
- [ 1] Git commit 信息清晰

### 设计审美
- [ 1] 配色协调统一
- [ 1] 排版整洁有序
- [ 1] 有交互动画效果
- [ 1] 参考了优秀设计
- [1 ] 在 README 中注明设计来源

### 文档完善
- [ 1] README 完整详细
- [ 1] 包含 AI 协作记录
- [ 1] 有项目运行说明
- [ 1] 有在线访问链接

### 部署成功
- [ 1] GitHub Pages 部署成功
- [1 ] 在线链接可正常访问
- [1 ] 在真机上测试过
- [1 ] 分享给朋友测试过

## 💡 加分项（可选）

想要更高的分数？考虑添加这些：

- 🎭 流畅的页面切换动画
- 🌍 国际化（中英文切换）
- 📊 技能可视化（进度条、雷达图）
- 📧 联系表单（集成 EmailJS 或 Formspree）
- 📝 集成博客（Markdown 渲染）
- 🎨 可自定义主题色
- ♿ 无障碍访问优化
- 🔍 SEO 优化
- 📈 Google Analytics 集成

## 🆘 常见问题

### 1. 部署后页面空白
- 检查 `vite.config.js` 中的 `base` 配置
- 确保 `package.json` 中的 `homepage` 正确

### 2. 路由刷新后 404
- GitHub Pages 不支持客户端路由
- 解决方案：使用 HashRouter 或添加 404.html 重定向

### 3. 图片加载失败
- 图片路径要使用相对路径
- 或使用 `import` 导入图片

### 4. 打包后 CSS 样式丢失
- 检查 CSS 文件是否正确导入
- 确认 Vite 配置是否正确

更多问题查看 [问题排查指南](../resources/troubleshooting.md)。

## 🎉 完成了？

恭喜你完成整个网页组寒假培训！

你现在已经掌握了：
- ✅ 现代前端开发完整流程
- ✅ React 框架实战经验
- ✅ 工程化思维和团队协作能力
- ✅ AI 辅助开发技能

**接下来你可以**：
- 继续完善你的个人主页
- 学习 TypeScript、Next.js 等进阶技术
- 参与开源项目
- 准备 iGEM 比赛的 Wiki 开发

---

**期待在 iGEM 比赛中看到你的精彩表现！** 🚀