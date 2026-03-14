# CloudVisor - 云监控管理平台

这是一个类似cloudvisor.co的云监控管理平台网站，提供完整的本地HTML网站解决方案。

## 网站结构

```
├── index.html          # 首页
├── features.html       # 功能页面
├── pricing.html        # 定价页面
├── contact.html        # 联系页面
├── styles.css          # 样式文件
├── script.js           # JavaScript交互文件
├── images/             # 图片文件夹
│   ├── logo.svg        # 网站Logo
│   ├── favicon.svg     # 网站图标
│   ├── dashboard.svg   # 仪表板示意图
│   ├── *-icon.svg      # 各种功能图标
│   └── *.svg           # 其他示意图
└── README.md           # 说明文档
```

## 主要功能

### 页面功能
- **首页**: 展示服务概览、核心功能和统计数据
- **功能页面**: 详细介绍监控功能和特性
- **定价页面**: 展示不同的服务方案和价格
- **联系页面**: 提供联系信息和表单

### 技术特性
- 响应式设计，支持移动端和桌面端
- 现代化的UI设计，使用渐变和阴影效果
- 平滑的动画和交互效果
- SVG图标和插图，确保清晰度
- 语义化的HTML结构
- 优化的CSS性能

### 交互功能
- 平滑滚动导航
- 卡片悬停效果
- 表单提交处理
- 导航栏滚动效果
- 按钮点击反馈

## 使用方法

1. 直接在浏览器中打开 `index.html` 文件
2. 或者使用本地服务器运行（推荐）：
   ```bash
   # 使用Python
   python -m http.server 8000
   
   # 使用Node.js
   npx serve .
   ```
3. 在浏览器中访问 `http://localhost:8000`

## 自定义修改

### 修改内容
- 编辑HTML文件中的文本内容
- 更新联系信息和公司详情
- 调整定价方案和功能描述

### 修改样式
- 编辑 `styles.css` 文件
- 修改颜色变量和主题
- 调整布局和间距

### 添加图片
- 将新图片放入 `images/` 文件夹
- 更新HTML中的图片引用
- 建议使用SVG格式以获得最佳效果

## 浏览器兼容性

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 许可证

此项目仅供学习和参考使用。