# Personal Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript, designed for GitHub Pages deployment.

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **GitHub Pages Ready**: Optimized for easy deployment on GitHub Pages
- **Git Integration**: Version control with Git and GitHub
- **Interactive Elements**: Smooth scrolling, mobile navigation, and form handling
- **Learning Focus**: Showcases Git, GitHub, and web development skills

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Version Control**: Git, GitHub
- **Deployment**: GitHub Pages
- **Fonts**: Inter (Google Fonts)
- **Icons**: Font Awesome

## 📁 Project Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── .gitignore         # Git ignore file
└── README.md          # Project documentation
```

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/portfolio-website.git
cd portfolio-website
```

### 2. Customize Your Information
1. Edit `index.html` to update:
   - Your name and title
   - Contact information
   - Project descriptions
   - Skills and technologies

2. Update `styles.css` to modify:
   - Color scheme
   - Typography
   - Layout and spacing
   - Animations

3. Modify `script.js` to add:
   - New interactive features
   - Form handling
   - API integrations

### 3. Deploy to GitHub Pages

#### Option A: Using GitHub Web Interface
1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select "Deploy from a branch" and choose "main"
5. Your site will be available at `https://yourusername.github.io/repository-name`

#### Option B: Using Git Commands
```bash
# Initialize Git repository
git init

# Add all files
git add .

# Commit changes
git commit -m "Initial commit: Portfolio website"

# Add remote repository
git remote add origin https://github.com/yourusername/portfolio-website.git

# Push to GitHub
git push -u origin main

# Enable GitHub Pages in repository settings
```

## 📚 Learning Objectives

This project demonstrates:

### Git & GitHub
- Version control with Git
- Repository management
- Branching strategies
- Commit best practices
- GitHub Pages deployment
- Pull requests and collaboration

### Web Development
- Modern HTML5 semantic elements
- CSS Grid and Flexbox layouts
- Responsive design principles
- JavaScript ES6+ features
- Web performance optimization
- Mobile-first design approach

### GitHub Features
- GitHub Pages hosting
- Repository management
- Issue tracking
- Pull request workflows
- GitHub Actions (optional)

## 🎨 Customization Guide

### Personal Information
Update the following sections in `index.html`:

1. **Hero Section** (lines ~30-40):
   ```html
   <h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
   <p class="hero-subtitle">Learning Git, GitHub & Web Development</p>
   ```

2. **Contact Information** (lines ~200-210):
   ```html
   <span>your.email@example.com</span>
   <span>github.com/yourusername</span>
   <span>linkedin.com/in/yourprofile</span>
   ```

3. **Project Links** (lines ~150-180):
   ```html
   <a href="https://github.com/yourusername/project-name" class="project-link" target="_blank">
   ```

### Color Scheme
The current color palette in `styles.css`:
- Primary: `#2563eb` (Blue)
- Secondary: `#fbbf24` (Yellow)
- Background: `#ffffff` (White)
- Text: `#1f2937` (Dark Gray)

To change colors, update the CSS variables or search and replace the color values.

### Adding New Sections
1. Add HTML structure in `index.html`
2. Add corresponding CSS in `styles.css`
3. Update navigation menu
4. Add JavaScript functionality if needed

## 📝 Git Workflow

### Initial Setup
```bash
# Clone the repository
git clone https://github.com/yourusername/portfolio-website.git
cd portfolio-website

# Create a new branch for customizations
git checkout -b feature/customize-portfolio

# Make your changes
# ... edit files ...

# Stage and commit changes
git add .
git commit -m "Customize portfolio with personal information"

# Push to GitHub
git push origin feature/customize-portfolio

# Create a Pull Request on GitHub
```

### Making Updates
```bash
# Pull latest changes
git pull origin main

# Create a new branch for updates
git checkout -b feature/add-new-section

# Make your changes
# ... edit files ...

# Stage and commit changes
git add .
git commit -m "Add new skills section"

# Push to GitHub
git push origin feature/add-new-section

# Create a Pull Request
```

## 🔧 Development Tips

### Local Development
1. Open `index.html` in your browser
2. Use browser developer tools to test responsive design
3. Make changes and refresh to see updates
4. Test on different devices and screen sizes

### GitHub Pages
- Changes pushed to the main branch automatically deploy
- Check deployment status in the Actions tab
- View your site at `https://yourusername.github.io/repository-name`

### Performance Optimization
- Optimize images before adding them
- Minify CSS and JavaScript for production
- Use web fonts efficiently
- Test loading speed with Google PageSpeed Insights

## 🚀 Advanced Features

### Custom Domain
1. Add a `CNAME` file with your domain name
2. Configure DNS settings with your domain provider
3. Update GitHub Pages settings

### GitHub Actions
Create `.github/workflows/deploy.yml` for automated deployment:
```yaml
name: Deploy to GitHub Pages
on:
  push:
    branches: [ main ]
jobs:
  deploy:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - name: Deploy to GitHub Pages
        uses: peaceiris/actions-gh-pages@v3
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          publish_dir: ./
```

### Analytics
Add Google Analytics or other tracking:
1. Get tracking code from Google Analytics
2. Add to `<head>` section in `index.html`
3. Track visitor behavior and site performance

## 🔍 Troubleshooting

### Common Issues
- **Site not updating**: Check if changes are pushed to main branch
- **Styling issues**: Clear browser cache and check CSS syntax
- **Mobile responsiveness**: Test on actual devices, not just browser dev tools
- **Git issues**: Check repository permissions and authentication

### Getting Help
1. Check GitHub Pages documentation
2. Review Git and GitHub guides
3. Search for solutions on Stack Overflow
4. Create an issue in the repository

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Support

If you encounter any issues or have questions:
1. Check the troubleshooting section above
2. Review Git and GitHub documentation
3. Create an issue in the GitHub repository
4. Reach out through the contact form on the website

---

**Happy Learning!** 🎉

This portfolio project is designed to help you learn Git, GitHub, and web development while creating something you can be proud of. Feel free to customize it and make it your own!