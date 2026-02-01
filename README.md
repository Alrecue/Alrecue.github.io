# Alrecue's Blog

This is the GitHub Pages repository for Alrecue's Blog.

## Development

### Prerequisites

- Node.js (v14 or higher)
- npm

### Setup

1. Clone the repository:
```bash
git clone https://github.com/Alrecue/Alrecue.github.io.git
cd Alrecue.github.io
```

2. Install dependencies:
```bash
npm install
```

### Development Server

Start the development server with live reload and SCSS watching:

```bash
npm run dev
```

This will:
- Start a local server at http://localhost:8080
- Watch SCSS files and automatically compile them to CSS
- Enable live reload for instant preview of changes

### Build

To build the CSS from SCSS:

```bash
npm run build
```

## Project Structure

- `scss/` - SCSS source files
- `css/` - Compiled CSS files (auto-generated)
- `js/` - JavaScript files
- `index.html` - Main page
- `2023/` - Blog posts from 2023
- `archives/` - Archive pages

## License

MIT
