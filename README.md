# 🌟 Modern Interactive Landing Page

<div align="center">
  <h3>
    <a href="https://html.x2y.qzz.io">查看在线演示 (Live Demo)</a>
  </h3>
  <p>一个采用现代玻璃拟态（Glassmorphism）设计风格，并带有丰富交互动效的个人主页/仪表盘前端项目。</p>

  [![GitHub Pages](https://img.shields.io/badge/Deployed%20on-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://html.x2y.qzz.io)
  [![Cloudflare](https://img.shields.io/badge/CDN-Cloudflare-f38020?style=for-the-badge&logo=cloudflare)](https://html.x2y.qzz.io)
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

</div>

---

## ✨ 核心特性 (Features)

本项目脱离了传统单一的纯静态排版，内置了多种提升用户体验的前端黑科技与微交互：

* 🖱️ **光晕追随鼠标 (Aura Cursor)**：全屏隐藏默认呆板的光标，取而代之的是平滑移动的绝对中心圆点与带有柔和呼吸感的发光光晕（Aura）。在悬停具有 `hover` 属性的按钮时，光晕会产生放大变色与吸附的磁性效果。
* 🎲 **3D 视差倾斜 (3D Parallax Tilt)**：卡片容器启用 `transform-style: preserve-3d` 与景深（Perspective）控制。当鼠标在屏幕范围移动时，中央的玻璃态卡片能精确计算相对坐标，产生极具空间包裹感的 3D 倾斜反馈。
* 📊 **动态数据仪表盘 (Animated Dashboard)**：卡片内部集成了「Core Skills（核心技能栈）」区域，在页面加载（延迟触发）时，通过 CSS 的动态计算变量实现流畅的进度条横向拉伸动画。
* 🔮 **磨砂玻璃与流光背景 (Glassmorphism & Gradients)**：采用极简高质感的毛玻璃拟态面板（运用 `backdrop-filter: blur`），底层背景分布了三个基于 CSS `animation` 缓缓浮动的多色渐变流光炫彩球体（Orb），彻底沉浸深邃的高级视觉氛围。
* 📱 **完全响应式 (Responsive Design)**：完美兼容移动端设备尺寸，并在移动端自动降级（移除悬浮和自定义光标等重渲染特性），确保手机端顺滑展示。

## 🛠️ 技术栈 (Tech Stack)

* **结构层 (HTML5)**: 响应式视口、清晰的语义化结构。引用了 Google Fonts (Outfit) 作为全局排版字体。
* **样式层 (Vanilla CSS3)**: 以最纯粹的原生 CSS 书写每一行动画 (`@keyframes`)、玻璃特效与组件排布。**完全零依赖**（未使用 Tailwind、Bootstrap 等重量级库），最大化极致性能。
* **逻辑层 (Vanilla JavaScript)**: 没有任何复杂的脚手架（React/Vue），仅通过不足 50 行的轻量级原生 JavaScript 精巧地处理 DOM 交互监听 (如 `mousemove` 坐标捕获)。

## 🚀 部署架构 (Deployment)

* **静态服务承载**: [GitHub Pages](https://pages.github.com/) (提供稳定零成本的 Serverless 存储与自动化 CI/CD 流水线)
* **自定义域名入口**: `html.x2y.qzz.io`
* **CDN 边缘加速网络**: 利用全球领军者 [Cloudflare](https://www.cloudflare.com/) 代理并加速流量，实现全站防攻击及双向全自动高强度 SSL/TLS 加密通信。

## 📝 本地启动指南 (Getting Started)

由于本项目采用了最纯粹的前端三剑客理念，如果您想克隆至本地把玩或者做二次修改，**过程简单到极致**：

1. 克隆代码至本地您的开发机：
   ```bash
   git clone https://github.com/xuxiangyu169/html-test.git
   ```
2. 无需运行 `npm install` 等繁琐命令配置环境。只需通过任何文件管理器找到刚才下载的 `index.html`，双击用浏览器打开它，一切魔法便会自动在眼前展开。
