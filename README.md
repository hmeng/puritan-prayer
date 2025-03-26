# Praying with the Puritans

A Jekyll-based online book exploring Puritan prayer traditions in an accessible, modern format.

## Project Overview

This project creates an online book that explores the rich prayer traditions of the Puritans, making their wisdom accessible to contemporary readers. The book is structured as a Jekyll site, making it easy to deploy on GitHub Pages.

## Site Features

- Clean, responsive design
- Chapter-based navigation
- Mobile-friendly layout
- Modern typography for easy reading
- Dropdown menus for chapter access

## Getting Started

### Prerequisites

To work with this project locally, you'll need:

- Ruby (version 2.5.0 or higher)
- RubyGems
- GCC and Make (on Unix-based systems)

### Installation

1. Install Jekyll and Bundler:
   ```
   gem install jekyll bundler
   ```

2. Clone this repository:
   ```
   git clone https://github.com/yourusername/puritan-prayer.git
   cd puritan-prayer
   ```

3. Install dependencies:
   ```
   bundle install
   ```

4. Start the local server:
   ```
   bundle exec jekyll serve
   ```

5. View the site at [http://localhost:4000/puritan-prayer](http://localhost:4000/puritan-prayer)

## Project Structure

```
puritan-prayer/
├── _config.yml           # Jekyll configuration
├── _layouts/             # Page layout templates
├── _includes/            # Reusable components
├── _chapters/            # Book chapters (markdown files)
├── _appendices/          # Book appendices (markdown files)
├── assets/               # Static assets
│   ├── css/              # Stylesheets
│   ├── images/           # Images
│   └── js/               # JavaScript
├── index.md              # Home page
└── about.md              # About page
```

## Adding Content

### Adding a New Chapter

1. Create a new markdown file in the `_chapters` directory with the following front matter:

```markdown
---
layout: chapter
title: "Your Chapter Title"
subtitle: "Optional Subtitle"
chapter_number: X
---

Your chapter content goes here.
```

2. Chapters are automatically sorted by the `chapter_number` field.

### Adding a New Appendix

1. Create a new markdown file in the `_appendices` directory with the following front matter:

```markdown
---
layout: appendix
title: "Your Appendix Title"
subtitle: "Optional Subtitle"
order: X
---

Your appendix content goes here.
```

2. Appendices are automatically sorted by the `order` field.

## Deployment

This site is designed to be deployed on GitHub Pages. To deploy:

1. Push your changes to GitHub:
   ```
   git add .
   git commit -m "Your commit message"
   git push origin main
   ```

2. Configure your repository's GitHub Pages settings to serve from the `main` branch.

## Customization

### Changing Colors and Styles

Edit the variables in `assets/css/main.css` to modify the site's color scheme:

```css
:root {
  --primary-color: #6a4c93;  /* Main purple color */
  --secondary-color: #8d99ae;
  --accent-color: #e07a5f;
  /* other color variables */
}
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details. 