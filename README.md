# Markdown-Weixin

把 Markdown 一键复制到微信公众号的工具，兼顾排版与代码展示。

- 在线体验: `http://md.nemoob.cn/`
- 项目主页: `https://github.com/nemoob/markdown-weixin`
- 关于我们: `https://nemoob.cn/`
- 公众号: 数码直白说

## 功能特性
- 一键复制，保留段落、列表、引用、加粗等常用样式
- 代码高亮与多主题，适配公众号编辑器的显示
- 可选择标题颜色，提升整体可读性
- 支持图片、链接、任务列表、脚注等 Markdown 语法
- 左右分栏实时预览，所见即所得

## 快速开始
1. 安装依赖：`npm install`
2. 构建产物：`npx webpack`
3. 本地预览：在 `dist/` 目录下启动服务，例如：
   - `python3 -m http.server 8000 --bind 127.0.0.1`
   - 打开 `http://127.0.0.1:8000/`

## 使用说明
- 在左侧输入或粘贴你的 Markdown 文本
- 顶部可选标题颜色（或保持默认）
- 点击“一键复制”，到公众号编辑器粘贴即可

## 项目结构
- `src/` 源码：`index.html`、`js/`、`css/`、`demo.md`
- `dist/` 构建输出：静态资源与页面
- `webpack.config.js` 构建配置

## 开发指南
- 主逻辑：`src/js/index.js`
- 样式与主题：`src/css/`
- 代码高亮主题：`src/css/themes/`

## 许可协议
MIT License。Copyright (c) 2025 Nemoob。
并感谢 Dom Christie 与 Fengda Huang 的早期贡献。

## 反馈与支持
- 提交 Issue：`https://github.com/nemoob/markdown-weixin/issues/new`
- 商务合作与交流：`https://nemoob.cn/`
