# Hearth Website

A modern Jekyll website for the Hearth startup, designed with a warm and inviting color scheme that reflects the brand's focus on home and hearth.

## Color Scheme

- **Primary Orange**: #E65E24
- **Light Orange**: #FC8F73  
- **Background**: #F9F8F3
- **Dark Brown**: #3F3022
- **Almost Black**: #090909

## Features

- **Responsive Design**: Mobile-first approach with beautiful layouts on all devices
- **Modern UI**: Clean, professional design with smooth animations and interactions
- **Jekyll Integration**: Built with Jekyll for easy content management and GitHub Pages deployment
- **Contact Form**: Functional contact form with validation
- **Navigation**: Easy navigation between Home and Contact pages

## Local Development

### Prerequisites

- Ruby 2.7 or higher
- Bundler gem

### Setup

1. Clone the repository
2. Install dependencies:
   ```bash
   bundle install
   ```

3. Serve the site locally:
   ```bash
   bundle exec jekyll serve
   ```

4. Open your browser to `http://localhost:4000`

### Building

To build the site for production:

```bash
bundle exec jekyll build
```

The built site will be in the `_site` directory.

## GitHub Pages Deployment

This site is configured to work with GitHub Pages. To deploy:

1. Push your code to a GitHub repository
2. Go to the repository settings
3. Navigate to the "Pages" section
4. Select "GitHub Actions" as the source
5. The site will automatically build and deploy when you push changes

### GitHub Actions Workflow

The site uses GitHub Actions for automatic deployment. The workflow will:
- Install Ruby and Jekyll dependencies
- Build the site
- Deploy to GitHub Pages

## File Structure

```
hearth-website/
├── _config.yml          # Jekyll configuration
├── _layouts/            # Page layouts
│   └── default.html     # Main layout template
├── assets/              # Static assets
│   ├── css/            # Stylesheets
│   ├── js/             # JavaScript files
│   └── hearth_logo.png # Brand logo
├── index.md            # Home page
├── contact.md          # Contact page
├── Gemfile             # Ruby dependencies
└── README.md           # This file
```

## Customization

### Adding New Pages

1. Create a new `.md` file in the root directory
2. Add front matter with layout and title:
   ```yaml
   ---
   layout: default
   title: Your Page Title
   description: Page description for SEO
   ---
   ```
3. Add your content in Markdown

### Updating Styles

The main stylesheet is located at `assets/css/style.css`. The CSS uses CSS custom properties (variables) for easy color customization.

### Modifying the Layout

The main layout template is in `_layouts/default.html`. This includes the navigation, header, and footer.

## Contact

For questions about this website or the Hearth startup, please visit our [Contact page](/contact) or email us at hello@hearth.com.

## License

© 2024 Hearth. All rights reserved.
