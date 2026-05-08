# MarkPreview — Real-time Markdown Previewer

A real-time Markdown previewer built with pure vanilla JavaScript — no libraries, no build step, no dependencies.

## Live Demo

🚀 [build-real-time-markdown-previewer-jq1bijk04-eso8484s-projects.vercel.app](https://build-real-time-markdown-previewer-jq1bijk04-eso8484s-projects.vercel.app)

## Features

- ⚡ Real-time preview with 300ms debounce
- 🎨 Syntax highlighting for JS, Python, HTML, CSS and more
- 🌗 Dark / Light theme toggle (persisted)
- 💾 Auto-save to `localStorage`
- 📄 Export to standalone HTML file
- ↔️ Draggable split divider (responsive — stacks vertically on mobile)
- 📊 Live word / character / line count
- ⌨️ Keyboard shortcuts: `Ctrl+B` bold, `Ctrl+I` italic, `Tab` → 2 spaces

## Markdown Support

- Headings (ATX `#` and Setext `===`)
- **Bold**, *italic*, ~~strikethrough~~, ==highlight==, `inline code`
- Fenced code blocks with language badge + copy button
- Blockquotes (nested)
- Ordered and unordered lists (nested)
- Task lists `- [x]`
- Tables with alignment
- Links, images, auto-links
- Horizontal rules

## Usage

No install needed. Open `index.html` in any modern browser.

```bash
git clone https://github.com/eso8484/build-real-time-markdown-previewer.git
cd build-real-time-markdown-previewer
open index.html
```

## Tech

Single `index.html` — vanilla JS, CSS custom properties for theming, pointer events API for drag, `localStorage` for persistence.
