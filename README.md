# 🌈 Dynamic-Background-Navigator

**动态背景 + 拟态设计，双版本网址导航页面。**

[![在线访问](https://img.shields.io/badge/在线访问-点击体验-blue)](https://aiyangdie.github.io/Dynamic-Background-Navigator)

![动态背景版演示](演示截图1.png)
![拟态版演示](演示截图.png)

---

## 📌 项目简介

Dynamic-Background-Navigator 提供两种风格的现代化网址导航页面：

- **🎨 动态背景版**（`docs/`）— 支持多张背景图片随机切换 + 文字颜色波浪动画，视觉冲击力强
- **🧊 拟态设计版**（`Neumorphic-Web-Navigator/`）— 深色拟态（Neumorphism）风格，简洁优雅

两个版本均为纯 HTML + CSS + JS 实现，零依赖，即开即用。

---

## ✨ 核心特性

### 🎨 动态背景版

- 🎭 **动态背景切换** — 支持多张背景图片自动轮播，6 秒切换
- 🌈 **文字颜色动画** — 链接文字 8 色波浪循环变化，永不重复
- 🔘 **手动切换** — 右上角按钮一键切换背景
- 🪟 **毛玻璃效果** — 半透明容器 + backdrop-filter，与背景完美融合
- 📱 **完全响应式** — CSS Grid 自适应布局，适配桌面 / 平板 / 手机
- ⚡ **智能检测** — 自动扫描 `images/` 文件夹获取背景图片

### 🧊 拟态设计版

- 🎨 **Neumorphism 风格** — 柔和阴影营造立体感，深色主题护眼
- 🖼️ **背景融合** — 半透明容器与背景图片自然融合
- 🚀 **轻量级** — 纯 HTML + CSS 实现，无 JavaScript 依赖
- 🎯 **易于定制** — 代码结构清晰，修改链接和样式简单直观

---

## 🛠️ 技术栈

| 技术 | 用途 |
|------|------|
| HTML5 | 语义化页面结构 |
| CSS3 | Grid 布局、渐变、动画、backdrop-filter、transition |
| JavaScript | 背景轮播、图片检测、文字颜色动画（仅动态版） |
| CSS Grid | 响应式网格布局 |

---

## 🚀 快速开始

### 前置条件

- 现代浏览器（Chrome / Firefox / Edge / Safari）

### 安装步骤

```bash
git clone https://github.com/aiyangdie/Dynamic-Background-Navigator.git
cd Dynamic-Background-Navigator
```

### 运行动态背景版

1. 将背景图片放入 `docs/images/` 文件夹（支持 PNG / JPG / GIF / WebP）
2. 在浏览器中打开 `docs/index.html`
3. 点击右上角按钮切换背景，享受动态效果

### 运行拟态设计版

1. 在浏览器中打开 `Neumorphic-Web-Navigator/index.html`
2. 根据需要修改链接和样式
3. 可替换 `bg.jpg` 自定义背景图片

---

## 📂 项目结构

```
Dynamic-Background-Navigator/
├── docs/                                # 🎨 动态背景版
│   ├── index.html                       # 主页面
│   ├── README.md                        # 版本说明
│   └── images/                          # 背景图片文件夹
├── Neumorphic-Web-Navigator/            # 🧊 拟态设计版
│   ├── index.html                       # 主页面
│   ├── bg.jpg                           # 背景图片
│   ├── 版本说明.md                       # 版本说明
│   └── README.md                        # 版本说明
├── 演示截图.png                          # 拟态版截图
├── 演示截图1.png                         # 动态背景版截图
├── CNAME                                # GitHub Pages 自定义域名
└── README.md                            # 项目说明
```

---

## 🤝 贡献与许可证

欢迎提交 PR 或 [报告问题](https://github.com/aiyangdie/Dynamic-Background-Navigator/issues)！

本项目采用 MIT 开源协议，您可以自由使用、修改和分发。

---

*🎭 让网址导航变得生动有趣*
