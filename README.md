# Joan Ressing - Personal Homepage

A clean, professional personal homepage built with Jekyll, showcasing my experience as a Data Scientist and Software Engineer based in the Netherlands.

## 🌟 Features

- **Responsive Design**: Mobile-first approach that works perfectly on all devices
- **Modern UI**: Clean, professional design with subtle animations and hover effects
- **Performance Optimized**: Fast loading with optimized assets and minimal JavaScript
- **SEO Ready**: Proper meta tags, structured data, and sitemap generation
- **GitHub Pages Compatible**: Ready to deploy on GitHub Pages

## 🛠️ Tech Stack

- **Jekyll**: Static site generator
- **SCSS**: For organized, maintainable styling
- **Vanilla JavaScript**: For smooth interactions and animations
- **Font Awesome**: For consistent iconography
- **Google Fonts**: Inter font family for modern typography

## 📁 Project Structure

```
├── _config.yml              # Jekyll configuration
├── _layouts/
│   └── default.html         # Main layout template
├── _data/                   # Content data files
│   ├── experience.yml       # Work experience data
│   ├── education.yml        # Education background
│   ├── skills.yml          # Technical skills
│   ├── publications.yml     # Publications & certifications
│   └── interests.yml        # Personal interests
├── _sass/                   # SCSS partials
│   ├── _variables.scss      # Design system variables
│   ├── _base.scss          # Base styles and typography
│   ├── _components.scss     # Reusable components
│   └── _sections.scss       # Section-specific styles
├── assets/
│   ├── css/main.scss       # Main SCSS file
│   └── js/main.js          # JavaScript functionality
├── index.html              # Main homepage
├── Gemfile                 # Ruby dependencies
└── test.html               # Static test version
```

## 🚀 Quick Start

### Prerequisites

- Ruby (version 2.7 or higher)
- Bundler gem
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/joanressing/joanressing.github.io.git
   cd joanressing.github.io
   ```

2. **Install Ruby dependencies**
   ```bash
   bundle install
   ```

3. **Serve the site locally**
   ```bash
   bundle exec jekyll serve
   ```

4. **Open your browser**
   Navigate to `http://localhost:4000`

### Alternative: View Test Version

If you don't have Jekyll installed, you can view a basic version by opening `test.html` in your browser.

## 🎨 Customization

### Content Updates

1. **Personal Information**: Update `_config.yml` with your details
2. **Experience**: Modify `_data/experience.yml` with your work history
3. **Education**: Update `_data/education.yml` with your academic background
4. **Skills**: Customize `_data/skills.yml` with your technical skills
5. **Publications**: Add your publications and certifications to `_data/publications.yml`
6. **Interests**: Update `_data/interests.yml` with your hobbies and interests

### Design Customization

1. **Colors**: Modify variables in `_sass/_variables.scss`
2. **Typography**: Update font settings in `_sass/_variables.scss`
3. **Layout**: Adjust spacing and layout in `_sass/_sections.scss`
4. **Components**: Customize buttons, cards, etc. in `_sass/_components.scss`

### Adding New Sections

1. Create a new include file in `_includes/`
2. Add corresponding styles in `_sass/_sections.scss`
3. Include the section in `index.html`
4. Update navigation in `_config.yml`

## 📱 Sections Overview

- **Hero**: Eye-catching introduction with call-to-action buttons
- **About**: Personal summary with key statistics
- **Experience**: Timeline of professional experience and internships
- **Education**: Academic background with coursework details
- **Skills**: Technical skills organized by category with progress indicators
- **Publications**: Research publications and professional certifications
- **Interests**: Personal hobbies and interests with icons
- **Contact**: Social media links and contact information

## 🎯 GitHub Pages Deployment

This site is configured for automatic deployment on GitHub Pages:

1. **Enable GitHub Pages** in your repository settings
2. **Set source** to "Deploy from a branch"
3. **Select branch** as `main` or `master`
4. **Your site** will be available at `https://joanressing.com`

### Custom Domain (Optional)

1. Add a `CNAME` file with your domain name
2. Configure DNS settings with your domain provider
3. Enable "Enforce HTTPS" in GitHub Pages settings

## 🔧 Development

### Local Development

```bash
# Install dependencies
bundle install

# Serve with live reload
bundle exec jekyll serve --livereload

# Build for production
bundle exec jekyll build
```

### File Watching

Jekyll automatically watches for changes and rebuilds the site. The `--livereload` flag enables automatic browser refresh.

## 📊 Performance Features

- **Optimized Images**: Responsive images with proper sizing
- **Minified CSS**: Compressed stylesheets for faster loading
- **Efficient JavaScript**: Minimal, optimized JavaScript
- **Lazy Loading**: Images load as needed
- **Caching**: Proper cache headers for static assets

## 🎨 Design System

### Colors
- Primary: `#2563eb` (Blue)
- Secondary: `#64748b` (Slate)
- Accent: `#06b6d4` (Cyan)
- Text: `#1e293b` (Dark slate)

### Typography
- Font Family: Inter
- Headings: 600-700 weight
- Body: 400 weight
- Small text: 500 weight

### Spacing
- Based on rem units
- Consistent spacing scale
- Responsive adjustments

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

- **LinkedIn**: [Your LinkedIn Profile](https://linkedin.com/in/your-profile)
- **GitHub**: [joanressing](https://github.com/joanressing)

---

Built with ❤️ using Jekyll and deployed on GitHub Pages.
