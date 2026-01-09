<p align="center">
  <a href="./README.md">简体中文</a> | <strong>English</strong>
</p>

# OpenHub.icu - open and icu

[OpenHub.icu](https://openhub.icu) designed to provide a clean, efficient, and pure frontend experience without the need for a backend.

## Tool List

Currently includes the following practical tools:

- **Markdown Live Preview**: Supports real-time rendering, code highlighting, mathematical formulas, and can be exported as high-definition long images, PDF (vector editable), or Word documents.
- **JSON Formatter**: Quickly format and validate JSON data.
- **Cron Expression Parser**: Visually parse and generate Cron expressions.
- **Regex Tester**: Real-time testing and validation of regular expressions.
- **Image Compressor**: Pure frontend image compression, protecting privacy.
- **Encoding Tools**: Base64, URL encoding/decoding, etc.

## Tech Stack

- **Core**: Native HTML5, JavaScript (ES6+)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) (CDN)
- **Deployment**: [Vercel](https://vercel.com/)


## Local Development

This project is a pure static website with no complex build process required.

1. Clone the project:
   ```bash
   git clone <repository-url>
   cd openhub.icu
   ```

2. Run:
   - Open `index.html` directly in your browser.
   - Or use any static server, for example:
     ```bash
     # Using Python
     python3 -m http.server

     # Using Node.js serve
     npx serve .
     ```

## 📝 License

MIT License
