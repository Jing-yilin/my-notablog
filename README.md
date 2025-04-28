# My NotaBlog

A minimalistic blog generated from Notion, using [Notablog](https://github.com/dragonman225/notablog).

## Features

- Content managed in Notion
- Automatically deploy to GitHub Pages every 20 minutes
- Beautiful and minimalistic design

## How it works

1. The content is managed in a Notion table
2. A GitHub Action workflow runs every 20 minutes
3. It generates static HTML files using Notablog
4. The static files are deployed to GitHub Pages

## Local Development

```bash
# Install dependencies
npm install

# Generate blog
cd notablog-starter
npx notablog generate .

# Preview blog (open public/index.html in your browser)
``` 