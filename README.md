<p align="center">
  <strong>简体中文</strong> | <a href="./README_EN.md">English</a>
</p>

# OpenHub.icu - open and icu

[OpenHub.icu](https://openhub.icu) 提供简洁、高效、无需后端的纯前端体验。

## 工具列表

目前包含以下实用工具：

- **Markdown 实时预览**: 支持实时渲染、代码高亮、数学公式，并可导出为高清长图、PDF (矢量可编辑) 或 Word 文档。
- **JSON 格式化**: 快速格式化和验证 JSON 数据。
- **Cron 表达式解析**: 可视化解析和生成 Cron 表达式。
- **正则测试**: 正则表达式实时测试与验证。
- **图片压缩**: 纯前端图片压缩，保护隐私。
- **编码转换**: Base64、URL 编码/解码等。

## 技术栈

- **核心**: 原生 HTML5, JavaScript (ES6+)
- **样式**: [Tailwind CSS](https://tailwindcss.com/) (CDN)
- **部署**: [Vercel](https://vercel.com/)

## 本地开发

本项目是一个纯静态网站，无需复杂的构建过程。

1. 克隆项目：
   ```bash
   git clone <repository-url>
   cd openhub.icu
   ```

2. 运行：
   - 直接在浏览器中打开 `index.html`。
   - 或者使用任意静态服务器，例如：
     ```bash
     # 使用 Python
     python3 -m http.server

     # 使用 Node.js serve
     npx serve .
     ```

## 📝 License

MIT License
