# 在线随机密码生成器 (Random Password Generator)

一个基于纯原生 HTML、CSS 和 JavaScript 构建的现代化在线随机强密码生成工具。无需后端，完全在浏览器端运行，安全可靠。

## ✨ 核心特性

- 🔐 **强密码生成**：支持自定义字符集（数字、小写、大写、特殊符号），可设定生成数量、密码长度范围，以及强制包含/排除特定字符。
- 🎨 **三种界面风格 (UI Styles)**：
  - `扁平化 (Flat)`：致敬 Windows 10 的 Modern UI，直角、极简、无阴影。
  - `圆角 (Rounded)`：现代 Web 应用风格，柔和的圆角与舒缓的阴影。
  - `玻璃质感 (Liquid Glass)`：极致还原 Apple Liquid Glass 概念，采用 `backdrop-filter` 深度模糊、边缘高光、内置流光和动态背景光斑，质感惊艳。
- 🌍 **多语言支持 (i18n)**：内置 20 种语言包，包含简体中文、繁体中文（台湾/香港）、法语（法国/比利时/加拿大/瑞士）、德语（德国/列支敦士登/奥地利/瑞士）、意大利语（意大利/瑞士）、葡萄牙语（巴西/葡萄牙）、文言文、英语、俄语、韩语、日语。
- 🖌️ **高度定制化**：内置 16 种预设主题色（涵盖 Windows 标准色及流行开发配色），支持自定义主题色，支持明亮、暗色及自定义背景模式。
- 🖱️ **沉浸式交互**：在 Liquid Glass 风格下，带有平滑跟随的鼠标光晕（Lerp 算法），光影会随主题色变化。
- 💾 **本地持久化**：使用 `localStorage` 自动保存用户的偏好设置（语言、风格、主题色等），刷新页面不丢失。

## 🛠️ 技术栈

- **HTML5**：语义化标签，无框架依赖。
- **CSS3**：CSS 变量 (CSS Variables) 驱动主题引擎，Flexbox/Grid 布局，`backdrop-filter` 实现毛玻璃，`mix-blend-mode` 实现光晕融合，关键帧动画。
- **Vanilla JavaScript**：无任何第三方库，纯原生 ES6+ 语法。包含 Fisher-Yates 洗牌算法、Lerp 平滑动画、Clipboard API、Blob 下载等。

## 🚀 快速开始

1. 克隆或下载本项目到本地：
   ```bash
   git clone https://github.com/你的GitHub用户名/your-repo-name.git