# TotemAI 官网

这是一个基于HTML、CSS和JavaScript的TotemAI智能创作生态平台官网。

## 功能特点

### 🎨 现代化设计
- 响应式布局，支持桌面和移动设备
- 玻璃效果和霓虹发光样式
- 流畅的动画和过渡效果
- 渐变色彩搭配

### 📱 完整的网站结构
- **导航栏**：固定顶部导航，包含CTA按钮
- **主视觉区域**：大标题和动态粒子背景
- **核心功能展示**：介绍Moma、Pika、Haku三大工具
- **工具组合说明**：展示三款工具的自由组合能力
- **使用场景展示**：详细的应用场景和时间估算
- **定价方案**：Free、Pro、Enterprise三种方案
- **行动召唤区**：促进用户注册和转化
- **页脚**：社交媒体链接和版权信息

### 🔧 技术栈
- **HTML5**：语义化标签和现代HTML
- **CSS3**：Flexbox、Grid、动画和渐变
- **Tailwind CSS**：快速样式开发
- **Font Awesome**：图标库
- **Google Fonts**：中文字体支持

## 快速开始

### 直接使用
1. 在浏览器中打开 `index.html` 文件
2. 网站会自动加载所有样式和功能

### 本地服务器（推荐）
```bash
# 使用Python启动本地服务器
python3 -m http.server 8000

# 或使用Node.js
npx serve .

# 然后在浏览器访问: http://localhost:8000
```

## 文件结构

```
totemai2c/
├── index.html          # 主页面文件
└── README.md           # 项目说明文档
```

## 浏览器兼容性

- ✅ Chrome (推荐)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ⚠️ IE11 (部分CSS特性可能不支持)

## 自定义修改

### 修改配色
在CSS的`:root`选择器中修改CSS变量：
```css
:root {
  --primary-color: #6366F1;
  --secondary-color: #EC4899;
  --background-color: #2E2F45;
}
```

### 修改内容
直接编辑`index.html`文件中的文本内容即可。

### 添加新功能
可以在现有基础上添加：
- 联系表单
- 博客系统
- 用户注册登录
- 产品演示视频

## 部署

### 静态托管
可以部署到以下平台：
- Vercel
- Netlify
- GitHub Pages
- 阿里云OSS
- 腾讯云COS

### 域名配置
1. 购买域名
2. 配置DNS解析
3. 设置HTTPS证书

## 性能优化

- 所有外部资源使用CDN加载
- 图片懒加载（如需要可添加）
- CSS和JS文件压缩
- 开启Gzip压缩

## 维护更新

### 定期检查
- 外部CDN链接的有效性
- 浏览器兼容性
- 移动端适配效果

### 内容更新
- 产品功能更新
- 价格调整
- 联系方式更新

---

© 2024 TotemAI. All rights reserved. 