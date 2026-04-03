# Colourful Codes

Colourful Codes is a lightweight, single-page web app for highlighting, formatting, comparing, and exporting source code.

It uses:
- **Highlight.js** for syntax highlighting
- **html2canvas** for PNG export

## Features

- **Language-aware highlighting**
  - Auto-detect mode
  - Manual language selection
  - Language list is filtered at runtime so only supported Highlight.js languages are shown

- **Theme switching**
  - Built-in theme selector
  - Instant theme changes through Highlight.js CSS themes

- **Auto-format**
  - JSON formatting via parse/stringify
  - HTML formatting with tag-aware indentation
  - Generic bracket-based indentation for C-style and similar code

- **Diff mode**
  - Side-by-side input areas for original and modified code
  - Line-based diff rendering with added/removed/unchanged markers
  - Diff stats summary for quick review

- **Output utilities**
  - Toggle line numbers
  - Toggle word wrap
  - Increase/decrease output font size
  - Copy highlighted output to clipboard
  - Export highlighted code block as PNG

## Project Structure

- `index.html` — complete application (UI, styles, and JavaScript logic)

## Usage

1. Open `index.html` in a browser.
2. Paste code into the editor.
3. Choose a language (or keep Auto Detect) and theme.
4. Click **Highlight Code**.
5. Optionally:
   - Click **Auto-Format Code**
   - Toggle line numbers or word wrap
   - Adjust font size
   - Copy output or export PNG
6. Switch to **Diff Mode** to compare two snippets.

## Notes

- This project is dependency-light and runs directly in the browser.
- Internet access is required to load external CDN assets.
