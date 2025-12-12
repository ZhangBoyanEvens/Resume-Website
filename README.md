# 个人简历作品集

一个现代化的个人简历作品集网站，使用 React + TypeScript + Tailwind CSS 构建。

## 功能特性

- 🎨 现代化的响应式设计
- ⚡ 基于 Vite 的快速开发体验
- 📱 移动端友好
- 🎭 流畅的动画效果
- 🔧 TypeScript 支持
- 🎨 Tailwind CSS 样式系统

## 技术栈

- **前端框架**: React 18
- **开发语言**: TypeScript
- **构建工具**: Vite
- **样式框架**: Tailwind CSS
- **路由**: React Router DOM
- **动画**: Framer Motion
- **图标**: Lucide React

## 项目结构

```
src/
├── components/          # 可复用组件
│   ├── Header.tsx      # 导航头部
│   └── Footer.tsx      # 页脚
├── pages/              # 页面组件
│   ├── Home.tsx        # 首页
│   ├── About.tsx       # 关于我
│   ├── Projects.tsx    # 项目作品
│   └── Contact.tsx     # 联系方式
├── App.tsx             # 主应用组件
├── main.tsx            # 应用入口
└── index.css           # 全局样式
```

## 快速开始

### 安装依赖

```bash
npm install
```

### 启动开发服务器

```bash
npm run dev
```

项目将在 http://localhost:3000 启动

### 构建生产版本

```bash
npm run build
```

### 预览生产版本

```bash
npm run preview
```

### 代码检查

```bash
npm run lint
```

```bash
npm run lint:fix
```

## 自定义配置

### 个人信息修改

1. 编辑 `src/components/Header.tsx` 中的网站标题
2. 修改 `src/components/Footer.tsx` 中的联系信息
3. 更新 `src/pages/About.tsx` 中的个人介绍
4. 编辑 `src/pages/Projects.tsx` 中的项目数据
5. 修改 `src/pages/Contact.tsx` 中的联系信息

### 样式定制

- 修改 `tailwind.config.js` 来自定义主题
- 编辑 `src/index.css` 来添加全局样式
- 在各组件中使用 Tailwind CSS 类名进行样式调整

## 部署

### Vercel 部署

1. 将代码推送到 GitHub
2. 在 Vercel 中导入项目
3. 配置构建命令: `npm run build`
4. 配置输出目录: `dist`

### Netlify 部署

1. 将代码推送到 GitHub
2. 在 Netlify 中连接 GitHub 仓库
3. 配置构建命令: `npm run build`
4. 配置发布目录: `dist`

## 许可证

MIT License
"# Resume-Website" 
