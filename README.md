# 🚀 CS Student's Blog - Hexo Terminal Theme

![Hexo](https://img.shields.io/badge/Hexo-8.1.1-blue?logo=hexo)
![Node.js](https://img.shields.io/badge/Node.js-≥16-green?logo=node.js)
![License](https://img.shields.io/badge/License-MIT-lightgrey)
![Theme](https://img.shields.io/badge/Theme-terminal__theme-orange)

A minimalist, terminal-style personal blog built with Hexo, designed for computer science students and developers who appreciate clean, functional aesthetics.

## ✨ Features

- **Terminal Interface**: Command-line inspired design with interactive elements
- **Responsive Layout**: Fully responsive across desktop, tablet, and mobile devices
- **Fast Performance**: Static site generation for optimal loading speeds
- **Syntax Highlighting**: Built-in support for code snippets with `highlight.js`
- **Tag & Category Support**: Organized content management system
- **Social Integration**: Ready for comments via utterances and social media links
- **Customizable Terminal**: Interactive terminal commands in theme configuration

## 📦 Installation

### Prerequisites
- Node.js 16 or higher
- Git

### Quick Start

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd blog
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Install Hexo CLI globally (optional)**
   ```bash
   npm install -g hexo-cli
   ```

## 🚀 Usage

### Local Development
```bash
# Start local server
hexo server
# or
npm run server
```

Access the blog at `http://localhost:4000`

### Create New Content
```bash
# Create a new post
hexo new "My New Post"

# Create a new page
hexo new page "about"
```

### Build & Deploy
```bash
# Clean generated files
hexo clean

# Generate static files
hexo generate
# or
npm run build

# Deploy (configure deployment in _config.yml)
hexo deploy
# or
npm run deploy
```

## ⚙️ Configuration

### Site Configuration (`_config.yml`)
Key settings for your blog:
```yaml
title: Your Blog Title
subtitle: A brief description
description: Your blog description
author: Your Name
language: en  # or your preferred language
timezone: Your/Timezone
theme: terminal_theme
```

### Theme Configuration (`themes/terminal_theme/_config.yml`)
Customize the terminal interface:
```yaml
terminal:
  home:
    - pwd:
      cmd: ssh YOUR_BLOG_URL
      outputs:
        - text: Welcome to YOUR_BLOG_NAME
```

## 🎨 Customization

### Adding Content
Place your Markdown posts in `source/_posts/` directory.

### Modifying Styles
Theme styles are located in `themes/terminal_theme/source/css/` using Stylus.

### Adding Pages
Create new pages in `source/` directory with corresponding Markdown files.

## 📁 Project Structure

```
blog/
├── _config.yml           # Hexo main configuration
├── package.json          # Dependencies and scripts
├── source/
│   ├── _posts/          # Blog posts (Markdown)
│   ├── tags/            # Tags page
│   └── about/           # About page
└── themes/
    └── terminal_theme/  # Terminal-style theme
        ├── layout/      # Pug templates
        ├── source/      # CSS, JS, images
        └── _config.yml  # Theme configuration
```

## 🤝 Contributing

Contributions are welcome! If you find any issues or have suggestions:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m 'Add some improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

The terminal_theme is included under its own license - refer to `themes/terminal_theme/LICENSE`.

## 🙏 Acknowledgments

- [Hexo](https://hexo.io/) - Fast, simple & powerful blog framework
- [terminal_theme](https://github.com/theme-terminal) - Terminal-style theme for Hexo
- All contributors and the open source community

---

**Built with ❤️ by a CS student sharing knowledge and experiences.**