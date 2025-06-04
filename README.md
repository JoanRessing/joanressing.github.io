# Joan Ressing - Personal Homepage

A clean, professional personal homepage built with Jekyll, showcasing my experience as a Data Scientist and Software Engineer based in the Netherlands.

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
- **Experience**: Timeline of professional experience and internships
- **Education**: Academic background with coursework details
- **Skills**: Technical skills organized by category with progress indicators
- **Publications**: Research publications and professional certifications
- **Interests**: Personal hobbies and interests with icons
- **Contact**: Social media links and contact information

## 🔧 Local Development

```bash
# Install dependencies
bundle install

# Serve with live reload
bundle exec jekyll serve --livereload

# Build for production
bundle exec jekyll build
```

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

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

- **LinkedIn**: [Joan Ressing](https://www.linkedin.com/in/joan-ressing-2751a6a0/)
- **GitHub**: [JoanRessing](https://github.com/joanressing)

---

Built with ❤️ using Jekyll and deployed on GitHub Pages.
