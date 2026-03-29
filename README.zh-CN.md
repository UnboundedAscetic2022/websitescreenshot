# Website Screenshot

把网站、HTML 和移动端页面导出为 **JPG、PNG、WebP 或 PDF**。

Website Screenshot 是一个面向真实使用场景的多语言截图与导出工具，适合需要把网页、HTML 模板或移动端页面快速保存成图片或文档的用户。它覆盖了 **网站截图**、**网页截图**、**HTML 转图片**、**HTML 转 PDF**、**iPhone 截图预览**、**Android 截图预览**、**整页截图**、**网页转 PDF** 等核心需求。

## 你可以用它做什么

- 把网站 URL 导出为 JPG、PNG、WebP 或 PDF
- 截取完整长页面，而不只是首屏
- 按 iPhone 和 Android 常见机型预览网页
- 把 HTML 和 CSS 渲染成图片或 PDF
- 保存 QA 记录、客户评审图、内部文档和归档资料

## 主要页面

- `website-screenshot`：网站 URL 截图与导出
- `html-screenshot`：把 HTML 和 CSS 转成图片
- `iphone-screenshot`：按常见 iPhone 尺寸预览网页
- `android-screenshot`：按常见 Android 机型预览网页
- `full-page-screenshot`：整页截图
- `website-to-pdf`：把网页保存成 PDF
- `html-to-pdf`：把 HTML 和 CSS 渲染成 PDF
- `website-full-page-screenshot`：截取完整长网页
- `iphone-full-page-screenshot`：截取 iPhone 尺寸的长移动页面
- `android-full-page-screenshot`：截取 Android 尺寸的长移动页面

## 适合哪些人

- 设计师做响应式检查
- QA 团队检查长页面、悬浮导航、CTA 和布局问题
- 增长与营销团队保存落地页和活动页预览
- 代理公司整理客户评审素材
- 产品团队记录页面变化
- 开发者导出 HTML 模板和组件预览

## 产品特点

- 一个工具支持多种导出格式
- 支持整页截图和长页面保存
- 内置常见手机机型尺寸
- 支持多语言页面和界面
- 支持接入 API 自动化流程

## 支持语言

- English
- 简体中文
- 日本語
- Deutsch
- 한국어
- Français
- Português (Brasil)
- العربية
- Русский
- Bahasa Melayu

## 本地启动

```bash
pnpm install
pnpm run build
PORT=3021 pnpm start
```

访问：

- `http://localhost:3021`

## 环境变量

常见配置包括：

- `HTML2IMAGE_API_BASE`
- `HTML2IMAGE_API_KEY`
- `NEXT_PUBLIC_HTML2IMAGE_API_BASE`
- `SITE_DOMAIN`
- `DEFAULT_FORMAT`

前端可以通过代理方式连接上游截图 API。

## API 说明

项目支持：

- 截图任务提交
- HTML 渲染任务
- 设备预设
- 整页截图
- PDF 导出
- Job 轮询

详见：

- [API_USAGE.md](/Users/ericwu/MinibuddyFolder/WebSite/40%20htmtoimage/htmltoimage-showcase/API_USAGE.md)

## 这不仅仅是一个工具页

这个项目同时也是一个多语言 SEO 站点，覆盖了这些高价值搜索需求：

- 网站截图
- 网页截图
- URL 转图片
- HTML 转图片
- HTML 转 PDF
- iPhone 截图
- Android 截图
- 整页截图
- 长网页截图
- 移动端整页截图

## 放到 GitHub 上适合用来做什么

- 展示产品能力
- 承接自然搜索流量
- 让用户快速理解主要功能
- 吸引开发者和潜在合作方
- 为 API 和产品试用引流
