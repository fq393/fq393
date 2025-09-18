# fq393 个人主页

一个现代化、响应式的个人主页网站，展示个人信息、技能、项目和联系方式。

## 🌟 特性

- **现代化设计**: 采用最新的设计趋势，简洁美观
- **完全响应式**: 适配所有设备，从手机到桌面
- **流畅动画**: 丰富的CSS动画和JavaScript交互效果
- **性能优化**: 快速加载，优秀的用户体验
- **SEO友好**: 良好的搜索引擎优化
- **无障碍访问**: 支持键盘导航和屏幕阅读器

## 🚀 功能

### 主要模块
- **首页**: 个人介绍和社交链接
- **关于我**: 详细的个人信息和统计数据
- **技能**: 技术栈展示，包含前端、后端、数据库等
- **项目**: 精选项目展示，包含项目描述和技术栈
- **联系**: 联系表单和联系方式

### 交互功能
- 平滑滚动导航
- 响应式移动端菜单
- 动态统计数字动画
- 表单验证和提交
- 返回顶部按钮
- 滚动时的元素动画
- 悬停效果和微交互

## 🛠️ 技术栈

- **HTML5**: 语义化标记
- **CSS3**: 现代CSS特性，包含Grid、Flexbox、动画等
- **JavaScript (ES6+)**: 原生JavaScript，无依赖框架
- **Font Awesome**: 图标库
- **Google Fonts**: 网络字体

## 📁 项目结构

```
fq393/
├── index.html          # 主页面
├── styles.css          # 样式文件
├── script.js           # JavaScript功能
└── README.md           # 项目文档
```

## 🎨 设计特色

### 颜色方案
- 主色调: `#6366f1` (靛蓝色)
- 辅助色: `#f59e0b` (琥珀色)
- 文本色: `#1f2937` (深灰色)
- 背景色: `#ffffff` / `#f9fafb`

### 字体
- 主字体: Inter (Google Fonts)
- 备用字体: 系统字体栈

### 布局
- 移动优先的响应式设计
- CSS Grid 和 Flexbox 布局
- 流体网格系统

## 🚀 快速开始

### 本地运行

1. 克隆项目到本地
```bash
git clone https://github.com/fq393/fq393.git
cd fq393
```

2. 使用本地服务器运行
```bash
# 使用Python
python -m http.server 8000

# 或使用Node.js
npx serve .

# 或使用PHP
php -S localhost:8000
```

3. 在浏览器中访问 `http://localhost:8000`

### 部署

#### GitHub Pages
1. 将代码推送到GitHub仓库
2. 在仓库设置中启用GitHub Pages
3. 选择主分支作为源

#### Netlify
1. 连接GitHub仓库到Netlify
2. 设置构建命令为空（静态站点）
3. 设置发布目录为根目录

#### Vercel
1. 导入GitHub仓库到Vercel
2. 自动部署，无需额外配置

## 🎯 自定义指南

### 修改个人信息

1. **基本信息**: 编辑 `index.html` 中的文本内容
2. **社交链接**: 更新 `.social-links` 中的链接地址
3. **技能标签**: 修改 `.skill-items` 中的技能列表
4. **项目展示**: 更新 `.project-card` 中的项目信息

### 样式自定义

1. **颜色主题**: 修改 `styles.css` 中的 CSS 变量
```css
:root {
    --primary-color: #your-color;
    --secondary-color: #your-color;
}
```

2. **字体**: 更改 Google Fonts 链接和 CSS 字体栈
3. **布局**: 调整网格和间距变量

### 添加新功能

1. **新页面部分**: 在 HTML 中添加新的 `<section>`
2. **导航链接**: 更新导航菜单
3. **样式**: 为新部分添加对应的CSS
4. **交互**: 在 `script.js` 中添加相关功能

## 📱 浏览器支持

- Chrome (推荐)
- Firefox
- Safari
- Edge
- 移动端浏览器

## 🔧 开发工具推荐

- **代码编辑器**: VS Code, Sublime Text
- **浏览器开发工具**: Chrome DevTools
- **设计工具**: Figma, Adobe XD
- **图标**: Font Awesome, Heroicons
- **字体**: Google Fonts

## 📈 性能优化

- CSS和JavaScript文件压缩
- 图片优化和懒加载
- 关键CSS内联
- 预加载重要资源
- 使用CDN加速

## 🤝 贡献

欢迎提交Issue和Pull Request来改进这个项目！

### 贡献步骤
1. Fork 项目
2. 创建功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 创建Pull Request

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

## 📞 联系方式

- **GitHub**: [https://github.com/fq393](https://github.com/fq393)
- **微信**: Van_1993
- **邮箱**: your.email@example.com

💡 **有任何想法可以联系一起探讨！**

## 🎯 GitHub Profile README

本项目还包含了一个专门的GitHub Profile README文件 (`PROFILE_README.md`)，你可以将其内容复制到你的GitHub同名仓库中来创建个人主页。

### 如何使用GitHub Profile README

1. **创建同名仓库**: 在GitHub上创建一个与你用户名相同的仓库（如：`fq393/fq393`）
2. **设置为公开**: 确保仓库是公开的
3. **复制内容**: 将 `PROFILE_README.md` 的内容复制到新仓库的 `README.md` 文件中
4. **个性化定制**: 根据你的实际情况修改个人信息、技能、项目等内容

### Profile README 特色功能

- 🎨 **动态打字效果**: 展示你的身份和技能
- 📊 **GitHub统计**: 自动显示你的代码统计信息
- 🏆 **成就徽章**: 展示你的GitHub成就
- 🐍 **贡献蛇动画**: 将你的贡献记录变成有趣的动画
- 🎵 **Spotify集成**: 显示你正在听的音乐
- 📝 **博客文章**: 自动更新最新博客内容
- 🛠️ **技能徽章**: 美观的技术栈展示

参考资料：[如何打造一个花里胡哨的Github个人主页](https://www.cnblogs.com/meet/p/18084942)

## 🙏 致谢

- [Font Awesome](https://fontawesome.com/) - 图标库
- [Google Fonts](https://fonts.google.com/) - 网络字体
- [Shields.io](https://shields.io/) - 徽章生成
- [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats) - GitHub统计
- [Readme Typing SVG](https://github.com/DenverCoder1/readme-typing-svg) - 动态打字效果

---

⭐ 如果这个项目对你有帮助，请给它一个星标！