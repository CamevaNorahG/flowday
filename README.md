# FlowDay 流日程

灵活的日程管理与行动记录工具，支持云同步。

## 功能

- 📅 日历视图与日期导航
- ✅ 任务管理与行动记录
- 🕐 时间线可视化
- 🔄 跨设备云同步（Firebase）
- 📱 移动端适配

## 本地开发

直接在浏览器中打开 `index.html` 即可使用（数据存储在本地）。

## 部署到 GitHub Pages

1. 创建 GitHub 仓库
2. 推送代码到 `main` 分支
3. 在仓库 Settings > Pages 中启用 GitHub Pages
4. GitHub Actions 会自动部署

## 启用云同步

1. 在 [Firebase Console](https://console.firebase.google.com/) 创建项目
2. 启用 Authentication（Email/Password）
3. 启用 Firestore Database
4. 复制 Firebase 配置到 `firebase-config.js`
5. 部署到 GitHub Pages

## 技术栈

- Vue 3 (CDN)
- Tailwind CSS (CDN)
- Firebase (Auth + Firestore)
