# ORBAT Map PWA 离线安装包

## 文件内容
- index.html：主网页
- manifest.webmanifest：PWA 配置
- service-worker.js：离线缓存
- icons/：主屏幕图标

## iPhone / iPad 使用方法

### 方法一：GitHub Pages
1. 新建一个 GitHub repository。
2. 上传本文件夹内的所有文件，不要只上传 zip。
3. 在 Settings → Pages 中启用 GitHub Pages。
4. 用 iPhone Safari 打开 GitHub Pages 网址。
5. Safari 分享按钮 → 添加到主屏幕。
6. 打开一次后，网页会被缓存；之后可离线使用。

### 方法二：Netlify / Vercel
1. 把整个文件夹拖到 Netlify Drop 或部署到 Vercel。
2. 用 iPhone Safari 打开生成的网址。
3. 分享 → 添加到主屏幕。
4. 之后可离线使用。

## 注意
Service Worker 离线缓存不能从 file:// 本地文件直接注册。
必须通过 HTTPS 网址打开一次，或 localhost 本地开发环境打开。
